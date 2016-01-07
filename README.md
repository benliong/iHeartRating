<img src="https://raw.github.com/garethpaul/iheartrating/master/assets/logo.png" alt="Logo" width="150" style="display:block; margin-left: auto;margin-right: auto"/>

# iHeartRating
Simple Ratings View for iOS enabling you to use any image as a rating e.g. hearts, stars, pigeons etc.

# Getting Started
You want to add `pod 'iHeartRating', '~> 0.1'` to your Podfile:

```
target 'MyApp' do
  pod 'iHeartRating', '~> 0.1'
end
```

## Sample Usage

Here is a ViewController :-

```
import iHeartRating
class ViewController: UIViewController, HeartRatingViewDelegate {

  override func viewDidLoad() {
        super.viewDidLoad()
  }


  func heartRatingView(ratingView: HeartRatingView, isUpdating rating:Float) {
      // do something while (rating) has been initiated
  }

  func heartRatingView(ratingView: HeartRatingView, didUpdate rating: Float) {
      // do something when (rating) object has been updates
  }

}
```
