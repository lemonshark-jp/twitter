# Twitter Clone

## Roadmap

-   [x] add hash to passwords when creating
-   [x] if auth, return to /home | /explore
-   [x] add regex validation to usernames / yup docs
-   [x] list tweets as last tweeted first
-   [x] add a static @ into username in login and sign up
-   [x] if name is not provided, get username in prisma schema
-   [x] refactor sign up and sign in forms
-   [x] break-word for description
-   [x] add env.example
-   [x] add modal for logout
-   [x] think about test account
-   [x] global loading
-   [x] add global loading as twitter bird with animation
-   [x] tweak useAuth, add loading state for auth loading instead of null
-   [x] optimistic update on likes
-   [x] unlike feature
-   [x] animation on click ? react spring/framer
-   [ ] handle errors like "user already exists"
-   [ ] add auth, also provide auth from google + apple
-   [ ] emote and photo upload to new tweet
-   [ ] add hidden/locked profile
-   [ ] add dark mode
-   [ ] lazy load tweets / react query implementation for lazy loading
-   [ ] avatar logic / image logic in tweets
-   [ ] make it responsive
-   [ ] progress bar for 280 characters
-   [ ] add card when hover on tweet profile & username
-   [ ] add twitter blue tick
-   [ ] make profile back arrow sticky | fixed
-   [ ] handle tweet text html-like breaks
-   [ ] change explore to home, home only followings
-   [ ] add delete options for users tweets
-   [ ] add skeletons for loading such as ... Tweets, description, images
-   [ ] animations on tweets
-   [ ] tooltips for likes/retweets and so on
-   [ ] global-error / error handling detailed
-   [ ] exlude password in prisma includes:{}, fix types accordingly
-   [ ] authorization for create/delete/like/follow and other api calls find out how next handles these, middleware?
-   [ ] follow/unfollow feature
-   [ ] message logic / socket io? feathers? how in next
-   [ ] cascade in postgresql / how to handle deleted tweets
-   [ ] supabase storage is ok to use for avatars and images? if not use aws
-   [ ] handle default avatar / twitter egg
-   [ ] make another prisma schema for replies, it needs to not count as a regular tweet
-   [ ] optimistic update on follow/unfollow
-   [ ] fix the logout sometimes not working as expected / ask gpt to how to make it more stable
-   [ ] single tweet page shows all replies or only first degree replies?
-   [ ] add a bar under the avatar if the tweet replies > 0
-   [ ] think about handling related errors in the fetch folder
-   [ ] block/unblock feature (optional, maybe in roadmap?)
-   [ ] how to add notifications? if really complex, hang it for later
-   [ ] search mechanism, only for users / users and tweets would be better
-   [ ] if auth, show random non-followed 3 people with avatars and has more than 1 followers for user to follow in right side
-   [ ] if possible and not too complex, add hashtags, @usernames and have a clickable link
-   [ ] add retweet and delete tweet logic
-   [ ] make a modal for unfollow confirmation
-   [ ] handle speed, somehow it feels slow, maybe it is different in production but nevertheless
-   [ ] handle loadings better, maybe add local next loading files?
-   [ ] change localhost to env or however next handles this
-   [ ] handle users trying to message themselves
-   [ ] add a most basic chatbot to show off messaging feature
-   [ ] complete profile reminder, edit page like /username/edit not modal
-   [ ] organize overall code/folders
-   [ ] admin privilages
-   [ ] material ui custom colors
-   [ ] delete all users and tweets before deploying, make it more presentable and maybe use faker.js
-   [ ] add report tweet feature, make the response automated somehow?
-   [ ] handle mui components' css better, using sx:{} while making it responsive
-   [ ] add snackbar for some feedback, copy from twitter
-   [ ] maybe tweets should be a markdown-like files for links/other stuff?
-   [ ] fix middleware, make it useful
-   [ ] is it ok to use useQuery with same keys multiple times in different components? if not refactor to make less api calls

check own twitter messages


