# Snappygram

Team project for weeks nine and ten of Makers Academy, creating a site that allows you to share and sell photos. Definitely not Instagram. Completed with [Jorja Hung](https://github.com/jorjahung), and [Nabin Rai](https://github.com/nabin369).

---

Snappygram lets you sign up (thanks to Devise), post photos (thanks to Paperclip and Amazon S3) and see the photos that other users have posted. It also lets you "buy" other photos (thanks to Stripe). If the email account's still up by the time you read this, it should also be able to send you an email confirming your purchase.

New photos are pushed into the timeline live (thanks to Pusher), and we also have infinite scrolling on the homepage, too. If you want more detail, there are views for all photos with a certain tag, or for all photos by a certain user.

Finally, if there's EXIF data attached to your photo, we use that to display more information about your snap on its page (thanks to the exifr gem). If that information contains location data, we can add a map as well (thanks, Google). And, if you click the globe button in the menu, you'll see a map of every photo that's been added to the service, which we think is pretty cool.