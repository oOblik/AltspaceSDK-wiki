### Guidelines for Contributing to the AltspaceSDK

When contributing code:
* Make changes in a branch named feature/my-new-feature and submit a Pull Request (PR).
* In your PR comment, note the Issue that your changes fix or implement.
* If no relavent Issue, create one on the [issues page](../issues).
* If adding or changing user-visible methods, update the [[SDK Reference]].
* Where possible, follow [Mr. doob's Code Style] used in the [Three.js] repo. 

Additional guidelines  
(from Three.js contributions guide)
* Create separate branches per patch or feature.
* Once done with a patch / feature do not add more commits to a feature branch (pull requests are not repository state snapshots, any change you do in that branch will be included in the pull request).
* If you add a new feature it's good to add also an example (both for showing how it's used and for testing it still works after eventual refactorings).
* If you add some assets for the examples (like textures, models, sounds, etc), make sure they have a proper license allowing for their use here (less restrictive the better).
* If you modify existing code (refactoring / optimization / bug fix), run relevant examples to check they didn't break or that there wasn't some performance regress.


[Mr. doob's Code Style]: https://github.com/mrdoob/three.js/wiki/Mr.doob%27s-Code-Style%E2%84%A2
[Three.js]: https://github.com/mrdoob/three.js 
