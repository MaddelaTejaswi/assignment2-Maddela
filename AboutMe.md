# Tejaswi Maddela
I come from the beautiful place the city of pearls. I love reading book. I like pani puri, chicken and Chocolates.

![link](https://static.wikia.nocookie.net/c7b51f6b-2d32-4674-89d1-342bc5956a2e)

******

# Country Table

| Name of the country | Reason | Time to spent(Days)
|---------------------------------|:-----------------------------------:|---------------------:|
| Dubai                           | for entertainment                   | 1 month              |
| Germany                         | for master's education              | 2 years              |
| Turkey                          | fun and chicken                     | 2 months             |
| Maldives                        | to experience beach                 | 2 weeks              |

******

# Quotes

> There is no sunrise so beautiful that it is worth waking me up to see it. _Tejaswi_

> People say money is not the key to happiness, but I have always figured if you have enough money, you can have a key made. _Tejaswi_

*******

> Getting first image from post

```php

function catch_that_image() {
  global $post, $posts;
  $first_img = '';
  ob_start();
  ob_end_clean();
  $output = preg_match_all('/<img.+?src=[\'"]([^\'"]+)[\'"].*?>/i', $post->post_content, $matches);
  $first_img = $matches[1][0];

  if(empty($first_img)) {
    $first_img = "/path/to/default.png";
  }
  return $first_img;
}
```

![link]( https://css-tricks.com/snippets/wordpress/get-the-first-image-from-a-post/)




