---
layout: page
title: Services
permalink: /services/
---

<div id='collection-component-29ff34dea88'></div>
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
      domain: 'meorator.myshopify.com',
      apiKey: 'c801aa348157a58ef1d65bc95576a637',
      appId: '6',
    });

    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('collection', {
        id: 79249768566,
        node: document.getElementById('collection-component-29ff34dea88'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "buttonDestination": "modal",
    "variantId": "all",
    "isButton": true,
    "contents": {
      "imgWithCarousel": false,
      "variantTitle": false,
      "options": false,
      "description": false,
      "buttonWithQuantity": false,
      "button": false,
      "quantity": false
    },
    "text": {
      "button": "DETAILS"
    },
    "styles": {
      "product": {
        "text-align": "left",
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      },
      "button": {
        "background-color": "#1b3946",
        "font-family": "Open Sans, sans-serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        ":hover": {
          "background-color": "#18333f"
        },
        "border-radius": "5px",
        "font-weight": "normal",
        ":focus": {
          "background-color": "#18333f"
        }
      },
      "variantTitle": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "title": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "normal",
        "color": "#0a191f"
      },
      "description": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "price": {
        "font-family": "Open Sans, sans-serif",
        "color": "#1b3a47",
        "font-weight": "bold"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold",
        "color": "#1b3a47"
      }
    },
    "googleFonts": [
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans"
    ]
  },
  "cart": {
    "contents": {
      "button": true
    },
    "text": {
      "notice": "Discount codes are added at checkout."
    },
    "styles": {
      "button": {
        "background-color": "#1b3946",
        "font-family": "Open Sans, sans-serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        ":hover": {
          "background-color": "#18333f"
        },
        "border-radius": "5px",
        "font-weight": "normal",
        ":focus": {
          "background-color": "#18333f"
        }
      },
      "footer": {
        "background-color": "#ffffff"
      }
    },
    "googleFonts": [
      "Open Sans"
    ]
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "variantTitle": false,
      "buttonWithQuantity": true,
      "button": false,
      "quantity": false
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
        "background-color": "#1b3946",
        "font-family": "Open Sans, sans-serif",
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px",
        ":hover": {
          "background-color": "#18333f"
        },
        "border-radius": "5px",
        "font-weight": "normal",
        ":focus": {
          "background-color": "#18333f"
        }
      },
      "variantTitle": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "title": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "normal"
      },
      "description": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "price": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "quantityInput": {
        "font-size": "18px",
        "padding-top": "17px",
        "padding-bottom": "17px"
      },
      "compareAt": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      }
    },
    "googleFonts": [
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans",
      "Open Sans"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Open Sans, sans-serif",
        "background-color": "#1b3946",
        ":hover": {
          "background-color": "#18333f"
        },
        "font-weight": "normal",
        ":focus": {
          "background-color": "#18333f"
        }
      },
      "count": {
        "font-size": "18px"
      }
    },
    "googleFonts": [
      "Open Sans"
    ]
  },
  "option": {
    "styles": {
      "label": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      },
      "select": {
        "font-family": "Open Sans, sans-serif",
        "font-weight": "bold"
      }
    },
    "googleFonts": [
      "Open Sans",
      "Open Sans"
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
  }
}
      });
    });
  }
})();
/*]]>*/
</script>