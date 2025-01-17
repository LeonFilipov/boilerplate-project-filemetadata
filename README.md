# File Metadata Microservice

This is a project for the **Back End Development and APIs** certification from freeCodeCamp. The API allows users to upload files and receive metadata about the uploaded file.
Instructions for building your project can be found at https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice


## Features

### `POST /api/fileanalyse`
- Accepts a form submission with a file upload.
- The file input field must have the `name` attribute set to `upfile`.
- Returns a JSON response containing metadata of the uploaded file, including:
  - **`name`**: The name of the uploaded file.
  - **`type`**: The MIME type of the file.
  - **`size`**: The size of the file in bytes.

#### Example Request:
Submit a form with a file in the `upfile` field.

#### Example Response:
```json
{
  "name": "example.txt",
  "type": "text/plain",
  "size": 128
}
