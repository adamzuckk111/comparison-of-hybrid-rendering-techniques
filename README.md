# Comparison of Hybrid Rendering Techniques 🎨🚀

Welcome to the **Comparison of Hybrid Rendering Techniques** repository! This project serves as a research monorepo for a master's thesis focused on rendering performance in React applications. Here, we explore various rendering techniques, compare their performance, and provide insights that can help developers make informed decisions for their projects.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-brightgreen)](https://github.com/adamzuckk111/comparison-of-hybrid-rendering-techniques/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [Topics Covered](#topics-covered)
3. [Research Objectives](#research-objectives)
4. [Rendering Techniques](#rendering-techniques)
5. [Performance Testing](#performance-testing)
6. [Setup and Installation](#setup-and-installation)
7. [Usage](#usage)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)
11. [Contact](#contact)

## Introduction

Rendering performance is crucial in modern web applications. With frameworks like React gaining popularity, understanding how different rendering techniques impact performance can lead to better user experiences. This repository provides a comprehensive study of hybrid rendering techniques, including Client-Side Rendering (CSR), Server-Side Rendering (SSR), Static Site Generation (SSG), and Incremental Static Regeneration (ISR).

## Topics Covered

This research focuses on the following topics:

- **CSR**: Client-Side Rendering
- **SSR**: Server-Side Rendering
- **SSG**: Static Site Generation
- **ISR**: Incremental Static Regeneration
- **RSC**: React Server Components
- **PSSR**: Partial Server-Side Rendering
- **Performance Testing**: Evaluating the performance of different rendering techniques

## Research Objectives

The main objectives of this research are:

1. **Compare Performance**: Analyze the performance differences between various rendering techniques in React applications.
2. **Identify Best Practices**: Discover best practices for implementing rendering techniques in real-world scenarios.
3. **Provide Insights**: Offer insights that can help developers choose the right rendering technique based on their application needs.

## Rendering Techniques

### Client-Side Rendering (CSR)

In CSR, the browser downloads a minimal HTML page and then uses JavaScript to render the content. This technique allows for dynamic user interactions but can lead to longer initial load times.

### Server-Side Rendering (SSR)

SSR generates the HTML on the server for each request. This method improves the initial load time and is beneficial for SEO. However, it can increase server load.

### Static Site Generation (SSG)

SSG pre-renders pages at build time. This technique is fast and efficient, making it ideal for content that doesn't change often. However, it lacks real-time data updates.

### Incremental Static Regeneration (ISR)

ISR combines the benefits of SSG and SSR. It allows for static pages to be updated incrementally, providing a balance between performance and up-to-date content.

### React Server Components (RSC)

RSC is a new experimental feature in React that allows developers to render components on the server. This can improve performance by reducing the amount of JavaScript sent to the client.

### Partial Server-Side Rendering (PSSR)

PSSR allows for parts of a page to be rendered on the server while other parts are rendered on the client. This hybrid approach can optimize performance for complex applications.

## Performance Testing

Performance testing is crucial for understanding how different rendering techniques impact user experience. In this repository, we have set up a series of tests to evaluate:

- Load times
- Time to Interactive (TTI)
- First Contentful Paint (FCP)
- Cumulative Layout Shift (CLS)

These metrics help us gauge the effectiveness of each rendering technique.

## Setup and Installation

To get started with this repository, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/adamzuckk111/comparison-of-hybrid-rendering-techniques.git
   cd comparison-of-hybrid-rendering-techniques
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the Application**:
   ```bash
   npm run dev
   ```

4. **Access the Application**: Open your browser and navigate to `http://localhost:3000`.

## Usage

This repository includes various examples demonstrating different rendering techniques. Each example is organized into its own folder, making it easy to navigate and test.

1. **Navigate to the Example**: Go to the folder of the rendering technique you want to test.
2. **Run the Example**: Follow the setup instructions provided in each folder.

## Results

The results of our performance tests can be found in the `results` folder. Each rendering technique is evaluated based on the metrics outlined earlier. This section provides graphs and charts that visually represent the performance data.

### Example Results

- **CSR vs. SSR**: CSR showed longer load times but better interactivity post-load, while SSR had faster initial load times.
- **SSG vs. ISR**: SSG had the fastest load times, but ISR provided a more dynamic experience without sacrificing speed.

## Contributing

We welcome contributions to this repository. If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [adamzuckk111](https://github.com/adamzuckk111)

Explore the research and insights provided in this repository. For downloadable releases, visit [here](https://github.com/adamzuckk111/comparison-of-hybrid-rendering-techniques/releases) to find the latest version of the project.