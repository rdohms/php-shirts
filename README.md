Shirts of the ElePHPant
=====================

This is an aggregator of PHP related shirts.
It's just a sculpin static website to help us have a single place to advertise all shirt being printed or available to buy now.

## Features

- Shirt can be: available, or not
- Multiple campaigns can be added to each shirt, in case you have US/EU based campaigns
- A mailing list can be attached to short so you can gauge interest in making new ones

### Adding your shirts

To add your own shirts, follow these steps.

- create a file in `source/_shirts`
- use this template to fill in

```
---
title: <title of your listing>
subtitle: <a subtitle for your listing>
stub: <your unique url and the name of the image>
available: <true|false> // will render campaigns or offer mailing list
mailing_list: <url to mailing list signup>

campaigns:
    <name>:
        region: <US | EU>
        link: <link to campaign>
        end_date: <date YYYY-MM-DD>
    <name>:
        region: <US | EU>
        link: <link to campaign>
        end_date: <date YYYY-MM-DD>


---
<description of listing>
```

- add your image to `source/images/shirts`
- open a PR

To test your PR locally, read up on Sculpin.
