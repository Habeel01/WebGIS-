# WebGIS- Attribute tool query
This project is a Web GIS application that uses OpenLayers and GeoExt for map visualization and interaction. Follow the steps below to set up and run the application.

## Prerequisites

1. **Apache Tomcat**: Download and install [Apache Tomcat](https://tomcat.apache.org/download-90.cgi) (version 9.0 or later is recommended).
2. **Web Browser**: Ensure you have a modern web browser installed (e.g., Chrome, Firefox, Edge).

## Installation and Setup

1. **Download Apache Tomcat**:
   - Visit the [Apache Tomcat download page](https://tomcat.apache.org/download-90.cgi).
   - Download the appropriate version for your operating system.
   - Install Apache Tomcat and ensure it is running.

2. **Add the Project Files**:
   - Copy the `query_panel.html` file and any associated resources (e.g., images, scripts, stylesheets) to the `webapps/test` directory inside your Apache Tomcat installation. For example:
     ```
     C:\Program Files (x86)\Apache Software Foundation\Tomcat 9.0\webapps\test
     ```

3. **Start Apache Tomcat**:
   - Open the Apache Tomcat control panel or terminal and start the server.

4. **Access the Application**:
   - Open your web browser and navigate to:
     ```
     http://localhost:8081/test/query_panel.html
     ```

5. **Verify the Application**:
   - Ensure the map and tools (e.g., zoom, pan, measure) are working as expected.

## Notes

- The application uses external libraries like OpenLayers and GeoExt. Ensure the URLS in the `<script>` and `<link>` tags in `query_panel.html` are accessible.
- If you encounter issues, check the browser console for errors and verify that all required resources are correctly loaded.


