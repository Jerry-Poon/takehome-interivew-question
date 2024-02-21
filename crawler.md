# TAKE HOME EXAM
write a crawler and a simple restful application.

## Requirements
- crawl data from this url: https://sinica.digitalarchives.tw/collection.php?type=3799
（only 臺灣本土植物數位化典藏）
  - can save data as json files or to a database, such as sqlite(bonus)
  - properties we need: 
    - 中文種名(string)
    - 學名(string)
    - 標本館號(string)
    - 編目號(string)
    - 引用(string)
    - 採集日期(date string)
    - 採集者(string)
    - 緯度(float)
    - 經度(float)
    - 國家(string)
    - 行政區(string)
    - 最低海拔(float)
    - image url(string)

- create a simple restful application with an endpoint to query the crawled specimens.
  - can written in node.js(Nest.js), python(fast api) or golang(gin)
  - use swagger ui to document the api
  - [bonus] create an endpoint to download the crawled data including image as a PDF.

- please use git to manage code and commit to github.
  - for reproducibility, please write a README.md to describe how to start the crawler and application.
  - [bonus] use docker to containerize the application
