Certainly! Here is the updated README without the particles.js feature:

---

# HTTP Request GUI

This project is a web-based GUI for making HTTP requests using different methods (GET, POST, PUT, DELETE) and displaying the responses in both tabular and graphical formats. It also includes a dynamic, animated background for enhanced visual appeal.

## Features

- **HTTP Methods**: Supports GET, POST, PUT, and DELETE requests.
- **Dynamic Input Fields**: Automatically shows/hides input fields based on the selected HTTP method.
- **Response Display**: Displays the response in an interactive table and a bar chart.
- **Animated Background**: Features a dynamic background animation using CSS.

## Technologies Used

- HTML
- CSS
- JavaScript
- Bootstrap
- Chart.js
- DataTables

## Setup and Usage

1. **Download the Code**: Download the HTML file containing the code.

2. **Open the HTML File**: Open the downloaded HTML file in a web browser.

3. **Make HTTP Requests**:
   - Select the HTTP method from the dropdown.
   - Enter the URL.
   - (Optional) Add headers in the textarea (one per line, in the format `Key: Value`).
   - For POST and PUT requests, enter the `name` and `price` values.
   - Click the **Send Request** button.

4. **View the Response**:
   - The response will be displayed in an interactive table.
   - A bar chart will visualize the response data.

## Code Breakdown

### HTML Structure

- **Form Section**: Contains input fields for HTTP method, URL, headers, name, and price.
- **Response Section**: Displays the response in a table and a chart.

### JavaScript Functions

- **toggleFields()**: Shows/hides the `name` and `price` fields based on the selected HTTP method.
- **sendRequest()**: Sends the HTTP request and processes the response.
- **flattenObject()**: Flattens nested objects for easier display in the table.
- **displayTableResponse()**: Populates the table with the response data.
- **displayChartResponse()**: Displays the response data in a bar chart.

### External Libraries

- **Bootstrap**: For responsive design and styling.
- **Chart.js**: For creating the bar chart.
- **DataTables**: For making the response table interactive.

### Example Usage

#### GET Request

1. Select `GET` from the method dropdown.
2. Enter the URL.
3. Click **Send Request**.

#### POST Request

1. Select `POST` from the method dropdown.
2. Enter the URL.
3. Add headers (optional).
4. Enter `name` and `price`.
5. Click **Send Request**.

## Troubleshooting

- Ensure the URL is correct and the server is running.
- Check the browser console for any error messages.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
---

This README provides an overview of the project, its features, setup instructions, and detailed information about the code and its usage. Feel free to modify it to better suit your specific needs.
