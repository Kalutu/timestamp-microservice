# Date Conversion API

This project is a basic API that allows you to convert between dates and Unix timestamps. It can handle a variety of date formats and provide the corresponding Unix timestamp and UTC representation.

## Features

- Convert dates to Unix timestamps.
- Convert Unix timestamps to UTC representations.
- Handle a wide range of date formats, including ISO dates, short dates, and long dates.
- Return error messages for invalid inputs.

## Usage

To use the Date Conversion API, you can make HTTP requests to the following endpoints:

### Convert Date to Timestamp

- **URL**: `/api/:date`
- **Method**: GET
- **Parameters**: `:date` - The date you want to convert. It should be a string in a format that can be successfully parsed by `new Date(date_string)`.
- **Response**: JSON object with the Unix timestamp and UTC representation.


## Contributing
Contributions are welcome! Please feel free to open an issue or create a pull request if you find any issues or have improvements to suggest.
