# Hüseyin Çağatay Çapar Law Office Website

A professional website for Hüseyin Çağatay Çapar Law Office built with ASP.NET Core.

## Features

- Responsive design
- Information about legal services
- Attorney biography
- Contact form
- Practice areas overview

## Technologies Used

- ASP.NET Core
- Bootstrap 5
- Font Awesome
- CSS3
- HTML5

## Deployment to Render

### Prerequisites

- A [Render](https://render.com) account
- A GitHub repository with this code

### Deployment Steps

1. **Push your code to GitHub**
   - Make sure your code is in a GitHub repository.

2. **Connect to Render**
   - Log in to your Render account.
   - Click "New" and select "Blueprint" from the dropdown menu.
   - Connect your GitHub repository.

3. **Configure the Service**
   - Render will automatically detect the `render.yaml` file and configure the service.
   - Verify the settings and click "Apply".

4. **Monitor Deployment**
   - Render will build and deploy your application automatically.
   - Once deployment is complete, you can access your website at the provided URL.

## Local Development

1. **Prerequisites**
   - .NET 8.0 SDK or later

2. **Run the application**
   ```
   dotnet run
   ```

3. **Access the website**
   - Open a browser and go to `https://localhost:5001` or `http://localhost:5000`

## Docker Support

This repository includes a Dockerfile for containerized deployment.

Build the Docker image:
```
docker build -t capar-law-office .
```

Run the Docker container:
```
docker run -p 8080:8080 capar-law-office
``` 