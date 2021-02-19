# Prehistoric Creatures Lab
--- 
For this lab, you're going to add a prehistoric creatures section to the `dinos` app.
---

## 1. Add a `prehistoric_creatures.json` file to your `dinos` directory. Give it the following data:
```javascript
[
  {
    "type":"giant beaver",
    "img_url":"http://www.beringia.com/sites/default/files/Giant-Beaver-banner.jpg"
  },
  {
    "type":"mastodon",
    "img_url":"https://cdn-images-1.medium.com/max/1200/1*a2VvYsKGApR-E1SnT5O7yQ.jpeg"
  },
  {
    "type":"saber-toothed salmon",
    "img_url":"https://cottagelife.com/wp-content/uploads/2014/11/Oncorhynchus_rastrosus.jpg"
  },
  {
    "type":"megalonyx",
    "img_url":"https://animalgeography.files.wordpress.com/2018/08/sloth-banner-e1535192925361.jpg?w=584&h=325"
  }
]
```


## 2. Update the dbTest.js file to create dinos based off `prehistoric_creatures.json`

**Hint 1:** You can `require()` any file, including .json files

**Hint 2 :** `bulkCreate()` works great with an array of data

Make sure that when you're finished, you can see the new prehistoric creatures inside of your `psql` database!

## 3. Create the following routes:

| VERB | URL | Action (CRUD) | Description |
|------|-----|---------------|-------------|
| GET | /creatures | Index (Read) | displays all prehistoric creatures |
| GET | /creatures/1 | Show (Read) | displays the type and photo of a particular prehistoric creature (id = 1) |
| GET | /creatures/new | New (Read) | shows a form for adding a new prehistoric creature |
| POST | /creatures | Create | creates an prehistoric creature with the POST payload data |


# Bonus!
## 4. Reorganize your routes into controllers
(one controller for dinosaurs and one controller for prehistoric creatures)
## 5. Add the remaining two CRUD routes, Update and Delete

