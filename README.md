# OpenTelemetry

To run:

1. Open terminal in the solution folder.
2. Run docker-compose up -d to start Jaeger.
3. Run the app, access Swagger UI, and execute the GET method.
4. Console traces will display a custom tag forecastsCount.
5. Visit http://localhost:16686, select OpenTelemetryApp as the Service, click FindTraces, open the WeatherForecast trace, span, and tags to view the custom forecastsCount tag.
