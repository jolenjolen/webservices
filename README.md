# 🌐 API-Enabled Web Services for Static Websites
Easily integrate dynamic, real-time data into your static websites using our lightweight JavaScript widgets. Whether you're building a blog, product page, or landing site hosted on GitHub Pages, Netlify, or Vercel — you can now display and interact with dynamic data without a backend.

## 🚀 Features
Plug-and-play script integration

No backend setup required — works with static hosting

All services are free to use with your API key

Easy customization via `data-` attributes

Lightweight and fast — suitable for production use

## 📦 Currently Available Web Services
|  Service Name   |                    Description                    |
| :-------------- | :------------------------------------------------ |
| `rating-widget` | Add 5-star rating systems to your website         |
| `feedback-widget` | Collect user feedback with ease                 |
| `user-widget` | Display dynamic user data or even login/logout users from your site             |

More widgets will be added soon...

## 🔧 Installation & Usage
**Step 1**: Get Your Free API Key

Head over to https://jolen.me/webservices/utils/register.html to generate your free API key.

**Step 2**: Add the Widget Script to Your Site

Include the following line in the `<head>` of your HTML:

```html
<script src="https://jolen.me/webservices/[SERVICE-NAME]/[SERVICE-NAME].js" data-api-key="[YOUR-API-KEY-HERE]"></script>
```

Replace:

`[SERVICE-NAME]` with the widget name you want to use (e.g. rating-widget)

`[YOUR-API-KEY-HERE]` with the API key you generated

**Step 3**: Use the Subwidgets in Your HTML

Each widget comes with customizable subcomponents.

Example: `rating-widget`

```html
<!-- Add a rating system for a specific product -->
<div class="rating-widget-rateHere" data-id="product123" data-username=""></div>

<!-- Display all ratings for a specific product -->
<div class="rating-widget-showAll" data-id="product123"></div>
```

Note: `data-id` should be a unique identifier for the item (e.g., product, post, etc.). `data-username` needs to be passed through. this can be done manually by you or you can use our `user-widget` to login the user, store their username, and call the username here. 

## 💡 Example Use Case

<h2>Rate this Product:</h2>
<div class="rating-widget-rateHere" data-id="product123" data-username="ff"></div>

<h3>All Ratings:</h3>
<div class="rating-widget-showAll" data-id="product123"></div>
<script src="https://jolen.me/webservices/rating-widget/rating-widget.js" data-api-key="abc123xyz"></script>

```html
<head>
  <script src="https://jolen.me/webservices/rating-widget/rating-widget.js" data-api-key="abc123xyz"></script>
</head>
<body>
  <h2>Rate this Product:</h2>
  <div class="rating-widget-rateHere" data-id="product123" data-username=""></div>

  <h3>All Ratings:</h3>
  <div class="rating-widget-showAll" data-id="product123"></div>
</body>
```

## 🤝 Contributing
Whether you're a beginner or a seasoned developer, your contributions are welcome!

|Ways to contribute|
|:--
|Improve existing functionality|
|Help write documentation or fix bugs|
|Suggest or build new widgets|


📧 Contact me directly at jolen@jolen.me if you’d like to collaborate or need help getting started.

|📅 Coming Soon|
|:--|
|Comment widgets|
|Poll widgets|
|Contact forms|
|Custom form data storage|
|More integrations and theme options|

## 🌍 License
MIT — Free for personal and commercial use.
