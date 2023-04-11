# Welcome to Fleet's _Capture the Flag_

Fleet Device Management couldn’t be more excited to announce that, Fleet has enabled MDM features in the latest release of Fleet as a public beta broadly available to everyone. Fleet is the first GitOps-enabled MDM solution, and we are showing that off with a little game of _Capture the Flag._ 

Check out the GitOps workflow by uploading your desktop background, updating the profile to use that image, and creating a pull request. Once approved, you will have 5 minutes to grab a screenshot from our live stream, post it on your favorite social media channel, and we will reward you with prizes!

### How to participate:

`tldr:` 

1.  Clone this repo.
2.  Create a branch.
3.  Add your desktop background image.
4.  Update the profile.
5.  Make a PR.

#### Clone the repo

```shell
git clone https://github.com/spokanemac/fleet-capture-the-flag
```

#### Add your desktop background image

Add your `3024 x 1964` image into `/desktop_pictures` and create a new branch.

_Please abide by our_ [_code of conduct_](https://github.com/fleetdm/fleet/blob/main/CODE_OF_CONDUCT.md)_. Your background will be live-streamed._

#### Update the profile

Update the [.mobileconfig profile](https://github.com/spokanemac/fleet-capture-the-flag/blob/8be2471224e11783aaef2e98ab046aa514e24a04/mdm_profiles/set_desktop_picture.mobileconfig#L19) with the name of your desktop background image without changing the path.

```
   <string>/Users/Shared/fleet-capture-the-flag/desktop_pictures/YOUR_DESKTOP_PICTURE.png</string>
```

#### Make a pull request

Make a pull request with your changes.
