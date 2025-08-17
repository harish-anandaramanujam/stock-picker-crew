# Stock Picker Crew

A multi-agent framework designed to simulate the behavior of stock analysts and portfolio managers.

## Overview

Stock Picker Crew is a cutting-edge system that leverages advanced algorithms and data analysis to provide users with informed investment decisions. This framework is designed to mimic the behavior of experienced stock analysts and portfolio managers, offering a reliable and efficient way to navigate the stock market.

### Agents

The Stock Picker Crew consists of four agents, each with a unique role and goal:

* **Trending Company Finder**: A Financial News Analyst that finds trending companies in a specified sector.
	+ Role: Financial News Analyst
	+ Goal: Find trending companies in the news for further research
	+ LLM: OpenAI GPT-4o-mini
* **Financial Researcher**: A Senior Financial Researcher that provides comprehensive analysis of each trending company.
	+ Role: Senior Financial Researcher
	+ Goal: Provide comprehensive analysis of each company in a report
	+ LLM: OpenAI GPT-4o-mini
* **Stock Picker**: A Stock Picker that selects the best company for investment based on research.
	+ Role: Stock Picker from Research
	+ Goal: Select the best company for investment and provide a detailed report
	+ LLM: OpenAI GPT-4o-mini
* **Manager**: A Manager that delegates tasks to achieve the goal of picking the best company for investment.
	+ Role: Manager
	+ Goal: Pick the best company for investment through a thorough process
	+ LLM: OpenAI GPT-4o-mini

## How it Works

1. The Trending Company Finder identifies trending companies in a specified sector.
2. The Financial Researcher provides comprehensive analysis of each trending company.
3. The Stock Picker selects the best company for investment based on research.
4. The Manager delegates tasks to achieve the goal of picking the best company for investment.

### Features

* **Multi-Agent Simulation**: Simulate the behavior of multiple stock analysts and portfolio managers to get a comprehensive view of the market.
* **Data-Driven Insights**: Leverage advanced data analysis to provide users with accurate and informed investment decisions.
* **Customizable**: Tailor the framework to suit your specific investment goals and risk tolerance.

## Getting Started

To get started with Stock Picker Crew, follow these steps:

1. Clone the repository: `git clone https://github.com/harish-anandaramanujam/stock-picker-crew.git`
2. Explore the codebase and configure the environment to suit your needs.
3. Utilize the framework to generate informed investment decisions.

## Contributing

Contributions are welcome. Feel free to submit pull requests and issues.

## License

This project is licensed under the terms specified in the LICENSE file.

## Contact

For more information, please contact [Harish Anandaramanujam](https://github.com/harish-anandaramanujam).

### Find Software Deals

If you want to post your first deal or find top software and SaaS deals for development, AI, no-code solutions, or hosting, check out [Dealsbe](https://dealsbe.com).
