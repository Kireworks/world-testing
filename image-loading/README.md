# Observation

Even though [image loading](https://creators.vrchat.com/worlds/udon/image-loading/) and [string loading](https://creators.vrchat.com/worlds/udon/string-loading/) using vrcurl() takes 5 seconds to load per image/string (VRChat enforced limit), once loaded into a world, more than one are already loaded by the time the world displays after joining.

# Test

A world with gray tiles (textured in-world) to load green tiles using vrcurl(). They are expected to load in randomly every 5 seconds, but I want to see how many are already loaded by the time I can see the world after joining an instance.