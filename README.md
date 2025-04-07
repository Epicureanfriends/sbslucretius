# Side By Side - Lucretius

# Side By Side - Diogenes Laertius Ten

This repo is a very simple implementation of a web page that displays four versions of the Public Domain text of Diogenes Laertius Book X.

It has been uploaded to Github to make it more feasible for volunteers to work together to make corrections in the text.

For questions, email Cassius Amicus at Cassius@EpicureanFriends.com, or better yet, ask about this at EpicureanFriends.com
1. Edit `index.html` and change `<script>html5Mode=false;</script>` to
   `<script>html5Mode=true;</script>`.
2. Make the web server redirect any requests for which the file doesn't exist
   to `index.html`. For apache, there's a `.htaccess` file included. Please
   note you need to change its `RewriteBase`.
