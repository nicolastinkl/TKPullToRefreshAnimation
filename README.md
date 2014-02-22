TKPullToRefreshAnimation
========================

 /** The sample data (not related to the animation) */ @property (strong) NSArray *primes;  /** The layer that is animated as the user pulls down */ @property (strong) CAShapeLayer *pullToRefreshShape;  /** The layer that is animated as the app is loading more data */ @property (strong) CAShapeLayer *loadingShape;  /** A view that contain both the pull to refresh and loading layers */
