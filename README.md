<h1>Minivisor</h1>

<p>
  <strong>Minivisor</strong> is a problem-solving web application designed to efficiently manage inventory. It offers a user-friendly interface for ordering products while <strong>automatically deducting</strong> the corresponding quantities from the inventory. With Minivisor, you can also <strong>add or remove inventory items</strong> as needed. Additionally, you can <strong>generate Telegram message-based reports</strong> for quantity and taste, and enjoy many more features.
</p>


<h2>Key Features</h2>
<ul>
  <li><strong>Automated Quantity Deduction:</strong> When you order a product, Minivisor <strong>automatically deducts</strong> the corresponding quantity from the inventory, simplifying the inventory management process.</li>
  <li><strong>Comprehensive Inventory Overview:</strong> Minivisor provides a complete overview of your inventory, displaying all relevant information.</li>
  <li><strong>Low Inventory Notifications:</strong> The application sends <strong>automatic notifications</strong> when an item's quantity falls below a certain threshold. This feature helps the café supervisor stay informed about low stock items and their impact on product availability.</li>
  <li><strong>Dependency Tracking:</strong> Minivisor identifies which products are dependent on low stock items. This information is crucial for the café supervisor to make informed decisions about product availability.</li>
  <li><strong>Daily Taste Test:</strong> The supervisor can manage list of specific items for <em>taste testing</em> every day. This information is communicated for maintaining the quality of cafe products.</li>
  <li><strong>Generated Message Report:</strong> The supervisor's daily taste test results are compiled into a message report displayed properly in the webapp iteself and sent via Telegram bot. The report provides valuable insights for further decision making.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Front-end and Back-end:</strong> Minivisor is built using <em>Nuxt.js</em>, which enables seamless development of both the front-end and back-end components of the application.</li>
  <li><strong>Database:</strong> <em>MongoDB</em> is used as the database system for efficient and reliable storage of inventory data.</li>
  <li><strong>Telegram Integration:</strong> Minivisor utilizes <em>GrammyJS</em> to send notifications, including the daily taste test information, and generate comprehensive reports via Telegram. The option to send reports through a Telegram bot or display them much more simple and beautifully with much more details within the web application is also available.</li>
</ul>

<h2>Installation and Setup</h2>
<ol>
  <li>Clone the repository: <code>git clone https://github.com/your-username/minivisor.git</code></li>
  <li>Install dependencies: <code>npm install</code></li>
  <li>Configure the MongoDB connection in the <code>.env</code> file.</li>
  <li>Start the application: <code>npm run dev</code></li>
</ol>

<h2>Usage</h2>
<ol>
  <li>Access the Minivisor web application in your browser.</li>
  <li>Browse the available inventory and place orders for products.</li>
  <li>Monitor low stock notifications and take appropriate actions to replenish inventory.</li>
  <li>Stay updated with the <strong>daily taste test</strong> provided by the supervisor.</li>
  <li>Explore the comprehensive reports or receive them via Telegram for detailed insights into your inventory and taste test results.</li>
</ol>

<h2>License</h2>
<p>
  The Minivisor project is licensed under the <a href="https://opensource.org/licenses/MIT">MIT License</a>. Feel free to modify and distribute the application according to the terms of this license.
</p>

<p>
  Thank you for using Minivisor to simplify your inventory management process and streamline the taste testing routine.
</p>
