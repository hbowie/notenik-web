| module   | action   | modifier        | object     | value                                                                   |
| -------- | -------- | --------------- | ---------- | ----------------------------------------------------------------------- |
| input    | set      |                 | xpltags    | false                                                                   |
| input    | set      |                 | dirdepth   | 1                                                                       |
| input    | open     | notenik-defined |            | /Users/hbowie/Sites/notenik-web/content                                 |
| filter   | clear    |                 |            |                                                                         |
| filter   | add      | eq              | Type       | include                                                                 |
| filter   | set      |                 | params     |                                                                         |
| sort     | clear    |                 |            |                                                                         |
| sort     | add      | ascending       | Title      |                                                                         |
| sort     | set      |                 | params     |                                                                         |
| template | webroot  |                 |            | /Users/hbowie/Sites/notenik-web                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/include-template.html         |
| template | generate |                 |            |                                                                         |
| input    | set      |                 | xpltags    | false                                                                   |
| input    | set      |                 | dirdepth   | 1                                                                       |
| input    | open     | notenik-defined |            | /Users/hbowie/Sites/notenik-web/content                                 |
| filter   | clear    |                 |            |                                                                         |
| filter   | add      | eq              | Type       | news                                                                    |
| filter   | set      |                 | params     |                                                                         |
| sort     | clear    |                 |            |                                                                         |
| sort     | add      | descending      | Date       |                                                                         |
| sort     | add      | ascending       | Page Title |                                                                         |
| sort     | set      |                 | params     |                                                                         |
| template | webroot  |                 |            | /Users/hbowie/Sites/notenik-web                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/news-page-template.html       |
| template | generate |                 |            |                                                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/latest-news-template.html     |
| template | generate |                 |            |                                                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/rss-template.xml              |
| template | generate |                 |            |                                                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/atom-template.xml             |
| template | generate |                 |            |                                                                         |
| input    | set      |                 | xpltags    | false                                                                   |
| input    | set      |                 | dirdepth   | 1                                                                       |
| input    | open     | notenik-defined |            | /Users/hbowie/Sites/notenik-web/content                                 |
| filter   | clear    |                 |            |                                                                         |
| filter   | add      | eq              | Type       | review                                                                  |
| filter   | set      |                 | params     |                                                                         |
| sort     | clear    |                 |            |                                                                         |
| sort     | add      | descending      | Date       |                                                                         |
| sort     | add      | ascending       | Page Title |                                                                         |
| sort     | set      |                 | params     |                                                                         |
| template | webroot  |                 |            | /Users/hbowie/Sites/notenik-web                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/reviews-include-template.html |
| template | generate |                 |            |                                                                         |
| input    | set      |                 | xpltags    | false                                                                   |
| input    | set      |                 | dirdepth   | 1                                                                       |
| input    | open     | notenik-defined |            | /Users/hbowie/Sites/notenik-web/content                                 |
| sort     | clear    |                 |            |                                                                         |
| sort     | add      | ascending       | Date       |                                                                         |
| sort     | add      | ascending       | Page Title |                                                                         |
| sort     | set      |                 | params     |                                                                         |
| template | webroot  |                 |            | /Users/hbowie/Sites/notenik-web                                         |
| template | open     |                 |            | /Users/hbowie/Sites/notenik-web/templates/content-template.html         |
| template | generate |                 |            |                                                                         |
| browse   | open     | url             |            | http://localhost/~hbowie/notenik-web/                                   |