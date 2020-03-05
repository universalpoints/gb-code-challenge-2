## The Guestbook Coding Challenge V2 Requirements

**Admin Image Search**

At some point in the future we'd like to build an internal portal for our admin users to search and download images from Imgur or Pixabay.

Here's an outline of what your application should do:
- [ ] When a user visits the homepage, it should ask them to create an account. After creating an account, a user should be signed in. Auth can be very simple. A separate login page and confirmation emails can be added bonuses.
- [ ] After creating an account, the user should see a search bar that will allow them to search for images.
- [ ] Searching should happen via AJAX. 
- [ ] Your search on the backend should first look at Pixabay for results before looking Imgur.
- [ ] For each resulting image, display metadata for that image such as name, general info, weight, height, source, and a way to directly download the image.
- [ ] The application should have notifications to inform users of a successful login, image results, or upon encoutering errors.
- [ ] A user should have a history of their previous searches and downloads.
- [ ] The app should look and feel good, as if it real users would actually use it. It should be responsive.

The application should have a README that explains clearly how to set it up and run it. We will attempt to run the application ourselves of course, so do us a favor by making it easy.

Docs: https://apidocs.imgur.com/?version=latest
client_id: `0d271c08bdac01c`
Sample Request: https://api.imgur.com/3/gallery/search?q=hollywood&client_id=0d271c08bdac01c

Docs: https://pixabay.com/api/docs/
key: `15499580-557f7f4e060df559b6cff71dd`
Sample Request: https://pixabay.com/api?key=15499580-557f7f4e060df559b6cff71dd&q=hollywood
