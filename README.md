## Lesson
    -> Create app as FrontEnd

1.remove git form front end and create git from source folder.
    command like - rm -rf .git

2.List foods
    1.Create Food model
    2.Create data.ts
        1.Add Sample food
    3.Add images to assets
    4.Create Food service
    5.Create Home component
        1.Add ts,html,css

3.Search
    1.Add method to food service
    2.Add search route
    3.Show search result in home component
    4.Generate search component
        1.Add to home component
        2.Add ts,html,css

4.Food Page
    1.Add method to food service
    2.Generate food page component
    3.Add route
    4.Add ts,html,css

5.Tags Bar
    1.Create tag model
    2.Add simple tag to data.ts
    3.Food Service
        1.Add get all tags method
        2.Add get all foods by tag method
    4.Add tags route
    5.Show tag result in home component
    6.Generate tags component
        1.Add to home component
        2.Add ts,html,css

6.Cart Page
    1.Create CartItem Model
    2.Create Cart Model
    3.Generate Cart Service
    4.Add to Cart button in Food Page
    5.Generate Cart page Component
        1.Add route
        2.Add ts,html,css

7.Not Found
    1.Generate Component
        1.Add ts,html,css
    2.Add to pages
        1.Home,Food,Cart page

8.Connect to backend
    1.Create backend folder
    2.npm init
    3.npm install typescript
    4.Create tsconfig.json
    5.Create .gitignore
    6.Copy data.ts to backend/src
    7.npm install express cors
    8.Create server.ts
        1.install @types
        2.Add apis
    9.npm install nodemon
    10.Add url.ts to frontend
    11.Add http client module
    12.Update food service
    