# BSky Tools

A collection of web-based tools for Bluesky social network users, built with vanilla JavaScript and HTML.

## Available Tools

### 1. Convert BSky Starter Pack to List

Converts a Bluesky starter pack into either a content list or moderation list. This tool allows you to:

- Import all users from a starter pack into a new list
- Choose between content or moderation list types
- Maintain the original pack name with "-Pack" suffix
- Automatically handle pagination for large starter packs

## Usage

### Converting a Starter Pack to List

1. Navigate to the [Starter Pack Converter](starter-to-list.html)
2. Enter your Bluesky handle (e.g., user.bsky.social)
3. Input your App Password (can be generated in [Bluesky Settings](https://bsky.app/settings/app-passwords))
4. Paste the URL of the starter pack you want to convert
5. Select the desired list type (Content or Moderation)
6. Click Submit and wait for the conversion to complete

## Security Note

This tool runs entirely in your browser. Your App Password is only used to authenticate with the Bluesky API and is never stored or transmitted elsewhere.

## Development

The project uses vanilla JavaScript and HTML for simplicity and ease of deployment. No build process or dependencies are required.

## Contributing

Feel free to contribute by submitting issues or pull requests on [GitHub](https://github.com/kevin-cunningham/bsky-tools).

## License

MIT License

## Author

Kevin Cunningham
