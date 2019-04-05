# gcp-app1-sviridov
A 'lean' ASP.NET Core 2.1 app that uses Razor Pages for server pages and React for some of the client functionality. The main goal of this example is to show how ASP.NET Core and modern client-side development can be combined in a simple, understandable way.

## Prerequisites
.NET Core 2.1 (or higher) SDK
Node.js 6.9.0 or higher

## Getting started
```
git clone https://github.com/Anatolii-Sviridov/gcp-app1-sviridov.git
cd LeanAspNetCore-React
dotnet run
```
Browse to https://localhost:5001 to see the working app.

At the first run, it takes a little while before all dependencies are resolved. Just have a little patience. After the first run, things are much faster.

## Deploy to GCP APP Engine using Google Cloud Build

```
gcloud builds submit --config=cloudbuild.yaml
```

The source code is taken from here https://github.com/martijnboland/LeanAspNetCore-React
