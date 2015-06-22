When it comes time to deploy your new web application, instead of sending down a dozen javascript and css files full of formatting and comments, this Django Application makes it simple to merge and compress JavaScript and CSS down into one or more files, increasing speed and saving bandwidth.

When in development, it allows you to use your original versions and retain formatting and comments for readability and debugging.

Because not all browsers will dependably cache javascript and css files with query string parameters, AssetPackager writes a timestamp into the merged file names. Therefore files are correctly cached by the browser AND your users always get the latest version when you re-deploy.

This code is released under the MIT license. You’re free to rip it up, enhance it, etc. And if you make any enhancements, I’d like to know so I can add them back in. Thanks!