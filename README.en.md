# Basearch

[中文](./README.md) | English

## Introduction

Basearch is an intelligent search tool designed to help users quickly find their bookmarked content through "text descriptions" by modeling the content of their favorites. This extension leverages advanced natural language processing and machine learning technologies to achieve efficient and accurate bookmark management and retrieval.

## Features

- **Intelligent Search**: Allows users to find bookmarked articles and URLs using natural language descriptions, without needing to remember specific bookmark names or URLs.
- **Vectorization Technology**: Converts the URLs of favorites into mathematical vectors, ensuring high accuracy in search results.
  Easy to Use: Features a simple and intuitive user interface, making it easy for users to get started quickly.
- **Cross-Browser Compatibility**: Supports major browser platforms, ensuring wide applicability.

## Source Code

### Front End

A browser extension is offered to customize the browser start page, supporting both traditional engine-based Internet search and personal favorite searches with a beautiful user interface and fluent animations.
Source code: https://github.com/shareAI2/basearch-app

### Backend API

Works in conjunction with the front end to synchronize user bookmark data, capture target webpage titles, content, and screenshots, and directly handle all business-related data sharing and services.
Source code: https://github.com/shareAI2/basearch-api

### Data Engine

Works with the backend to read and write bookmark databases, vector databases, extract content summaries from bookmarked articles, insert blocks into personal knowledge bases, and perform similarity calculations.
Source code: https://github.com/shareAI2/basearch-engine

## How to Use

- Chrome: https://github.com/shareAI2/basearch-app/releases/download/v0.1.0/basearch.zip
- Edge: https://github.com/shareAI2/basearch-app/releases/download/v0.1.0/basearch.zip

1. Download and unzip the browser AI extension package into a folder, then select "Settings - Extensions - Install unpacked extension" to install the plugin. Open a new browser tab to use Basearch.
1. Enter a description of the target URL in the search bar, such as "blogs related to data science."
   The plugin will search for matching URLs in the favorites based on the description and display the search results.
   Contributions
1. We welcome any form of contribution! If you have any suggestions, questions, or requests, please submit an issue or create a pull request. Thank you for your support!

## License

This project is licensed under the Apache License.

## Contact Us

For any questions, please contact us at:

Email: ai-lab@foxmail.com
Thank you for trying out Basearch!
