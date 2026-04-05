# Erlang C Calculator

A web-based calculator for call center staffing and performance metrics using the Erlang C formula.

## Description

This tool helps call center managers and telecom professionals calculate key performance indicators for staffing decisions. Based on the Erlang C traffic model, it provides insights into agent utilization, service levels, and queue management.

## Features

- **Traffic Load Calculation**: Computes Erlang load (A = λ × AHT/3600)
- **Agent Utilization**: Shows percentage of agent time spent handling calls
- **Service Level**: Calculates percentage of calls answered within target time
- **Average Speed of Answer (ASA)**: Estimates average wait time for callers
- **Queue Probability**: Erlang C probability that a caller will queue
- **Staffing Recommendations**: Suggests minimum agents needed for stable queues
- **Interactive Chart**: Visualizes service level vs. agent count relationship

## Input Parameters

- **Call Arrival Rate (λ)**: Calls per hour reaching the center
- **Average Handle Time (AHT)**: Total time per call (talk + hold + after-call work)
- **Active Agents**: Number of simultaneously available agents
- **Service Level Target**: Time threshold for service level calculation (e.g., 80% within 20 seconds)

## Usage

1. Open `erlang.html` in any modern web browser
2. Adjust the input sliders for your call center parameters
3. View real-time calculations and recommendations
4. Use the chart to explore staffing scenarios

## Technologies

- HTML5
- CSS3 (with dark mode support)
- Vanilla JavaScript
- Chart.js for data visualization

## Browser Support

Works in all modern browsers with JavaScript enabled. No server required - runs entirely client-side.

## License

MIT License

## Contributing

Feel free to submit issues and enhancement requests.
