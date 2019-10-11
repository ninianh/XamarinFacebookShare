# XamarinFacebookShare
Quick open facebook-share-dialog for xamarin forms

 # Installation
 
 from nuget https://www.nuget.org/packages/XamarinFacebookShare/


 - Android:
   XamarinFacebook.Droid.FacebookDroid.Init("yourAppId");
   
 - iOS:
  XamarinFacebook.iOS.FacebookiOS.Init("yourAppId");
  
 # Usage:
   - On your shared project
 
               XamarinFacebook.FeedStory feedStory = new XamarinFacebook.FeedStory();
               feedStory.Path = "https://github.com/ninianh/XamarinFacebookShare";
               feedStory.Description = "ABC";
               await XamarinFacebook.FacebookFactory.Instance.FeedPost(feedStory);
