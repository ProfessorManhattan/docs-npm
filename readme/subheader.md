<h4>
  <a href="{{ website.homepage }}">Homepage</a>
  <span> | </span>
  <a href="{{ profile.npmjs }}">NPM Profile</a>
  <span> | </span>
  <a href="https://www.npmjs.com/package/{{ pkg.name }}">NPM Package</a>
  <span> | </span>
  <a href="{{ repository.group.npm }}/{{ slug }}/-/blob/master/CONTRIBUTING.md">Contributing</a>
  <span> | </span>
  <a href="{{ chat_url }}">Chat</a>
  <span> | </span>
</h4>
<p>
  <a href="{{ repository.group.npm }}/{{ slug }}">
    <img alt="Version" src="https://img.shields.io/badge/version-{{ version }}-blue.svg?cacheSeconds=2592000" />
  </a>
  <a href="{{ website.documentation }}/npm" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="{{ repository.group.npm }}/{{ slug }}/-/raw/master/LICENSE" target="_blank">
    <img alt="License: {{ license }}" src="https://img.shields.io/badge/License-{{ license }}-yellow.svg" />
  </a>
  <a href="https://twitter.com/{{ profile.twitter }}" target="_blank">
    <img alt="Twitter: {{ profile.twitter }}" src="https://img.shields.io/twitter/follow/{{ profile.twitter }}.svg?style=social" />
  </a>
</p>
