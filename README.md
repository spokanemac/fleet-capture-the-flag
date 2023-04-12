# Welcome to Fleet's _Capture the Flag_

![fleet-catch-the-flag](https://user-images.githubusercontent.com/6200229/231500664-5b5d14b6-795d-49fa-8a70-5e107e4cb23e.png)

[Fleet Device Management](https://fleetdm.com/) couldn’t be more excited to announce that MDM features have been enabled in the latest release. The public beta is broadly available to everyone and Fleet is the first GitOps-enabled MDM solution.  We are showing that off with a little game of _Capture the Flag._ 

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

_Please abide by our_ [_code of conduct_](https://github.com/fleetdm/fleet/blob/main/CODE_OF_CONDUCT.md)_. Your background will be [live-streamed](https://www.twitch.tv/fleetdm)._

#### Update the profile

Update the [.mobileconfig profile](https://github.com/spokanemac/fleet-capture-the-flag/blob/8be2471224e11783aaef2e98ab046aa514e24a04/mdm_profiles/set_desktop_picture.mobileconfig#L19) with the name of your desktop background image without changing the path.

```
   <string>/Users/Shared/fleet-capture-the-flag/desktop_pictures/YOUR_DESKTOP_PICTURE.png</string>
```

#### Make a pull request

Make a pull request with your changes.

#### Claim your prize

Check the [live stream](https://www.twitch.tv/fleetdm). Once your PR is approved and merged, your desktop background image will be displayed for 5 minutes.

Take a screen capture, and post it on your favorite social media channel, tagging Fleet and using the hashtag #fleetgitops
- Mastodon: https://discuss.systems/@Fleet
- Twitter: https://twitter.com/fleetctl
- Facebook: https://www.facebook.com/fleetdm/
- LinkedIn: https://www.linkedin.com/company/fleetdm
- osquery Slack: https://osquery.slack.com/archives/C01DXJL16D8
- MacAdmins Slack: https://macadmins.slack.com/archives/C0214NELAE7

We will contact you with how to claim your Fleet gear.

1 entry per person, void where prohibited.
