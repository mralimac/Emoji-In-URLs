# Emoji-In-URLs

By mralimac

A quick guide on having Emojis in a URL

## Why bother with this?
Although this can be seen as a fairly useless or gimmicky feature to have, it may have some useful applications.

For example, instead of http://example.com/christmas you could use a Christmas-related Emoji (🎄) in the URL, making it become http://example.com/🎄 . This means a user has to write less and you get a shorter URL that would be easier to print in an advertising campaign

You should also consider how much of Internet Traffic is done on smartphones and other mobile devices. Most of which can support emojis natively, we may reach a point where everyone has the ability and knowledge to use Emojis quite soon

## Information about this
### Apache
If you run an apache server, you can use the .htaccess file. Make sure you replace [php code] with the PHP src for each Emoji. I would advise you add Apple's and Google's code for each one as they use different codes.
You can also edit the server's conf file to add these redirects which is better than using a .htaccess file. The language is virtually the same

### Nginx
If you run a Nginx server, you should use the nginx.conf file. Don't actually copy paste the file into your server setup. Just take the code from this github and paste in the correct place.
