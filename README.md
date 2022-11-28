# in-app review

To implement in-app review in your application:

1) Initialize RatingManager(context, String feedbackMail)
2) Call ratingManager.setupRatingFlags() in your activity onCreate()
3) Then call ratingManager.startRatingFlow(activity) when you want to show review dialogs
