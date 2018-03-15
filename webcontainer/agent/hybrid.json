{
  "$jason": {
    "head": {
      "title": "Jasonbase",
      "actions": {
        "visit": [
          {
            "{{#if /\\/edit/.test($jason.url)}}": {
              "type": "$href",
              "options": {
                "url": "{{$jason.url.replace('/edit', '')}}",
                "preload": {
                  "background": "#ffffff"
                }
              }
            }
          },
          {
            "{{#else}}": {
              "type": "$default"
            }
          }
        ]
      }
    },
    "body": {
      "background": {
        "type": "html",
        "url": "https://www.jasonbase.com",
        "action": {
          "trigger": "visit"
        }
      }
    }
  }
}
