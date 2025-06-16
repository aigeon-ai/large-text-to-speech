# Large Text to Speech MCP Server

## Overview

The **Large Text to Speech** MCP server is a robust solution designed for handling large-scale text-to-speech synthesis tasks. It excels in processing extensive volumes of text, making it ideal for applications that require the conversion of large text bodies into high-quality spoken audio.

### Key Features

- **Asynchronous Processing**: The server operates on a job-based system, allowing you to submit large texts for conversion without needing immediate results. This feature is perfect for applications where time-sensitive processing is not required.

- **High Volume Capability**: Capable of processing texts with virtually no size limit, the server can handle substantial inputs, such as 12,000 words or 72,000 characters, which can result in audio outputs of over an hour in length.

- **Accessibility**: Once processing is complete, the resulting audio files are accessible via a direct download link, valid for 24 hours.

## Tools and Functionality

The server provides two primary tools for interacting with its services:

1. **Create TTS Job**:
   - **Functionality**: This tool allows you to initiate a text-to-speech job by submitting the text you want to be converted into speech.
   - **Description**: Request the conversion of large text into an audio file with human-like voice quality.

2. **Get Job Status**:
   - **Functionality**: This tool enables you to check the status of your submitted text-to-speech job.
   - **Description**: Retrieve the current status and results of your job, including the estimated time of completion (ETA) and the download link once the job is complete.

## Usage

The Large Text to Speech MCP server is straightforward to use, requiring you to submit a text for conversion and then check back to see the processing status. The server handles the heavy lifting, processing your text asynchronously and providing you with a download link once complete.

### Billing and Limitations

- **Character-Based Billing**: Usage is billed based on the number of characters submitted. Each 1,000 characters consume one quota, making it easy to estimate costs based on your text size.
- **Practical Limitations**: While the server can handle large inputs, be mindful of practical limitations imposed by endpoint protocols, such as HTTP request size limits.

## Conclusion

The Large Text to Speech MCP server offers a powerful and flexible solution for converting large volumes of text into high-quality speech. Its asynchronous processing capabilities and high volume handling make it an excellent choice for applications that need to convert extensive text bodies into audio efficiently.