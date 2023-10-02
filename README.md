## This is a template project for Blazor Server

#### It includes:

- Docker
- Tailwind
- Mudblazor

#### Docker instructions

Create image:
dotnet publish

Run image:
docker run --name projectname -p 8080:80 -d projectname:1.1.0

Stop image:
docker stop "number"

#### Tailwind instructions

Create minified css:
npx tailwindcss -i ./Styles/app.css -o ./wwwroot/app.css --minify