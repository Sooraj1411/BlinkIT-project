<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blinkit Sales Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1, h2 {
            color: #333;
        }
        section {
            margin-bottom: 20px;
        }
        .key-features, .visualizations {
            list-style: none;
            padding: 0;
        }
        .key-features li, .visualizations li {
            margin-bottom: 10px;
        }
        .clear-slicers-btn {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 15px;
            text-align: center;
            cursor: pointer;
            border-radius: 5px;
        }
        .clear-slicers-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Blinkit Sales Dashboard</h1>

    <section>
        <h2>Overview</h2>
        <p>This Power BI dashboard provides a comprehensive analysis of sales data for Blinkit, India’s Last Minute App. The dashboard offers insights into key performance indicators (KPIs), sales distribution by various dimensions, and trends over time, enabling stakeholders to make data-driven decisions.</p>
    </section>

    <section>
        <h2>Key Features</h2>
        <ul class="key-features">
            <li><strong>Total Sales:</strong> $1.20M overall sales displayed for a quick overview.</li>
            <li><strong>Average Sales:</strong> $141, showing the average revenue per transaction or item.</li>
            <li><strong>Number of Items:</strong> 8,523 items sold in total.</li>
            <li><strong>Average Rating:</strong> A customer rating of 3.9 stars, reflecting user satisfaction.</li>
            <li><strong>Sales Breakdown:</strong> Distribution of sales by fat content, outlet size, item type, and location tiers.</li>
            <li><strong>Trends Over Time:</strong> Outlet establishment trends from 2012 to 2022, illustrating sales growth and changes.</li>
            <li><strong>Outlet Performance:</strong> Analysis of outlet types by total sales, number of items, average sales, average rating, and item visibility.</li>
        </ul>
    </section>

    <section>
        <h2>Slicers</h2>
        <p>To provide flexibility in data exploration, the dashboard includes slicers for:</p>
        <ul>
            <li>Outlet Location Type</li>
            <li>Outlet Size</li>
            <li>Item Type</li>
        </ul>
        <p>These slicers allow users to filter the data according to specific criteria and gain insights into different aspects of the business.</p>
        <button class="clear-slicers-btn">Clear Slicers</button>
        <p>Click the "Clear Slicers" button to clear all filters and return to the default view.</p>
    </section>

    <section>
        <h2>How to Use</h2>
        <ul>
            <li><strong>Filter Data:</strong> Use the slicers on the left to filter the data by different dimensions such as outlet type, size, and item type.</li>
            <li><strong>Explore Insights:</strong> Analyze KPIs and visualizations to understand sales performance, outlet distribution, and trends over time.</li>
            <li><strong>Clear Filters:</strong> Click the Clear Slicers button to reset all filters and return to the default view.</li>
        </ul>
    </section>

    <section>
        <h2>Visualizations</h2>
        <ul class="visualizations">
            <li><strong>KPIs:</strong> Provides a summary of key metrics like Total Sales, Average Sales, Number of Items, and Average Rating.</li>
            <li><strong>Pie Chart:</strong> Displays the sales distribution by Fat Content (Low Fat vs. Regular).</li>
            <li><strong>Bar Chart:</strong> Ranks item types by total sales, allowing you to see top-performing categories.</li>
            <li><strong>Line Chart:</strong> Tracks outlet establishment and sales growth from 2012 to 2022.</li>
            <li><strong>Donut Chart:</strong> Shows sales distribution by outlet size (Small, Medium, High).</li>
            <li><strong>Stacked Bar Chart:</strong> Highlights sales by Outlet Location (Tier 1, Tier 2, Tier 3).</li>
            <li><strong>Table:</strong> Compares outlet types across various metrics including sales, rating, and item visibility.</li>
        </ul>
    </section>

    <section>
        <h2>Requirements</h2>
        <p>Power BI Desktop or Power BI Service to view and interact with the dashboard.</p>
    </section>

    <section>
        <h2>Additional Notes</h2>
        <p>The dashboard is optimized for quick insights and provides a visual representation of sales data. All data has been anonymized and is used solely for demonstration purposes.</p>
    </section>

    <section>
        <h2>Contact</h2>
        <p>For any questions or feedback, please reach out to [Your Contact Information].</p>
    </section>
</body>
</html>
