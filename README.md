# angular-app

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.12.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.


1. create 2 files: posts.html (inside views) and posts.js(inside controller)

2. Create a new route that points to the view file and injects the controller
3. Include js controller in the index.html file.

4. to add and remove posts, we modifiy the controller. We need to create a post object inside this controller that will have the attributes of a post (a link and a title).

5. Users will create a form through our view, so we need to modify post.html