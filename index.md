---
title: Minimal-Neon
---
<h2>Recent Blog Posts</h2>

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ site.url }}{{ post.url }}" class="link">
      <time class="">{{ post.date | date_to_string }} </time>
      : {{ post.title }}
    </a>
  </li>
  {% endfor %}
</ul>

Minimal-Neon is a Jekyll Theme inspired by computer terminals perfect for tech blogs.

## Roadmap

See the [open issues](https://github.com/ronynn/jekyll-theme-comics/issues) for a list of proposed features (and known issues).

## Project philosophy

The minimal-neon theme is something I always wanted to put together. It gives the futuristic vibe one gets from the movies and yet remains eye pleasing and readable. 

The theme structure is intended to make it quick and easy for users to create a website, it provides the user the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout).

## Contributing

Interested in contributing? I'd love your help. Minimal-Neon is an open source project.

## Author

[ronynn](https://github.com/ronynn)

