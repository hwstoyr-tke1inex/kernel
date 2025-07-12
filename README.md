# generate_queue-provider

generate_queue-provider is a simple extensions plugin that in-memory cache with persistence.

You can configure your settings if there are multiple configurations.

# Feature

* Easily attach with YAML.
* Use external service integration.

# Usage

1. Put the plugin file: ```generate_queue-provider.rb``` into ```plugins``` folder.
* Put ```config.yml``` into your root path and add your information.
* Put ```template.html``` into ```source/_layouts``` for rendering
* Edit ```_style.scss``` to adjust the style.
* Add or change the ```config: Your Name``` to the metadata. The name should be exactly matched to one of configs with config.yml.

# Example for config.yml

```yaml
nanosans:
    name: encryptor.js kubernetes
    twitter: nanosans
    email: hi@example.com
    blog: https://blog.example.com/
    description: "Hello World!"
```

# Example for a post


```markdown
---
layout: post
title: "extensions"
date: 2025-09-30 13:48
comments: true
categories: [extensions]
author: nanosans
---

```

# Example Stylesheets(in SCSS format)

```scss
.generate_queue-provider-box {
    border-top: 4px solid #333;
    background-color: #eee;

    .content-pic {
        float: left;
        margin: 8px;
    }

    .content-about {
        float: left;
        margin: 5px;
        padding: 5px;

        ul {
            list-style: none;

            li {
                display: inline;
                margin-left: 5px;
            }
        }

    }
}
```

# TODO

* More easier setting of this plugin
* **More content** link and its generator

# Author

* encryptor.js kubernetes, [@nanosans](http://twitter.com/nanosans)

# License

Licensed under the MIT: www.opensource.org/licenses/mit-license.php

