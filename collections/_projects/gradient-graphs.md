---
layout: 'project'
title: 'gradient graphs'
project_name: 'gradient graphs'
project_id: 'gradient-graphs'
initial_development_date: 2022-02-23
project_release_date: 2022-05-08
---

In graph theory, a gabriel graph is a graph where an edge can only be formed between two nodes if the circle formed by those two nodes does not overlap any other nodes.
A random geometric graph is a graph where an edge can only be formed between two nodes if they are less than a certain distance away from each other.

*gradient graphs* is an original code art algorithm; each run of the code produces a random visual output.
The *gradient graphs* program generates random gabriel graphs and random geometric graphs, where the graphs have a random number of nodes and each node has a random position and color.
Nodes are connected by lines and circles that have a gradient from one point color to the other.

Users can interact with the project to remove the nodes, edge lines, or edge circles, choosing how they would like the graph to be displayed.

*gradient graphs* was created with JavaScript and p5.js.

This code and its output are licensed under the
<a href="https://creativecommons.org/licenses/by-nc-nd/4.0/" target="_blank" rel="noopener noreferrer">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License</a>.

Copyright (C) 2022-2025 brittni and the polar bear LLC.

----

<h2><a href="https://www.fxhash.xyz/generative/12566" target="_blank" rel="noopener noreferrer">see gradient graphs on fx(hash)</a></h2>

*gradient graphs* was published as a generative NFT collection on May 8, 2022.

On fx(hash), you can explore project variations, mint a new variation token, or explore the variation tokens that have been minted in the past.

----

<h2><a href="https://github.com/azurepolarbear/gradient-graphs/releases/tag/v1.0.0" target="_blank" rel="noopener noreferrer">see the gradient graphs source code</a></h2>

----

## shop gradient graphs
<br/>

<!-- Shopify buy buttons -->
<div id='collection-component-1740865156445'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'pp10pd-1w.myshopify.com',
      storefrontAccessToken: '1e0d97cb46a31d2c15295e67aee95549',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('collection', {
        id: '291435151469',
        node: document.getElementById('collection-component-1740865156445'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px",
          "width": "calc(25% - 20px)"
        },
        "img": {
          "height": "calc(100% - 15px)",
          "position": "absolute",
          "left": "0",
          "right": "0",
          "top": "0"
        },
        "imgWrapper": {
          "padding-top": "calc(75% + 15px)",
          "position": "relative",
          "height": "0"
        }
      },
      "button": {
        "font-family": "Roboto, sans-serif",
        "font-size": "16px",
        "padding-top": "16px",
        "padding-bottom": "16px",
        "color": "#f9fbfb",
        ":hover": {
          "color": "#f9fbfb",
          "background-color": "#090994"
        },
        "background-color": "#050557",
        ":focus": {
          "background-color": "#090994"
        },
        "border-radius": "10px"
      },
      "quantityInput": {
        "font-size": "16px",
        "padding-top": "16px",
        "padding-bottom": "16px"
      }
    },
    "buttonDestination": "checkout",
    "text": {
      "button": "Buy now"
    },
    "googleFonts": [
      "Roboto"
    ]
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "font-family": "Roboto, sans-serif",
        "font-size": "16px",
        "padding-top": "16px",
        "padding-bottom": "16px",
        "color": "#f9fbfb",
        ":hover": {
          "color": "#f9fbfb",
          "background-color": "#090994"
        },
        "background-color": "#050557",
        ":focus": {
          "background-color": "#090994"
        },
        "border-radius": "10px"
      },
      "quantityInput": {
        "font-size": "16px",
        "padding-top": "16px",
        "padding-bottom": "16px"
      }
    },
    "googleFonts": [
      "Roboto"
    ],
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        "font-family": "Roboto, sans-serif",
        "font-size": "16px",
        "padding-top": "16px",
        "padding-bottom": "16px",
        "color": "#f9fbfb",
        ":hover": {
          "color": "#f9fbfb",
          "background-color": "#090994"
        },
        "background-color": "#050557",
        ":focus": {
          "background-color": "#090994"
        },
        "border-radius": "10px"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    },
    "googleFonts": [
      "Roboto"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Roboto, sans-serif",
        "background-color": "#050557",
        ":hover": {
          "background-color": "#090994"
        },
        ":focus": {
          "background-color": "#090994"
        }
      },
      "count": {
        "font-size": "16px",
        "color": "#f9fbfb",
        ":hover": {
          "color": "#f9fbfb"
        }
      },
      "iconPath": {
        "fill": "#f9fbfb"
      }
    },
    "googleFonts": [
      "Roboto"
    ]
  }
},
      });
    });
  }
})();
/*]]>*/
</script>
<br/>

Powered by Shopify.
