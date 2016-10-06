### kubernetes-reviewers-configuration

This configuration file is used to updated OWNERS files in github.com/kubernetes/kubernetes. Please file a pull request if you 
notice inaccurate information relating to yourself. Potential reviewers may signal willingness to review particular paths in
the repository; agreements to review paths serve as a filter to be applied _after_ automatic path attribution has been applied. Potential reviewers may also blacklist particular paths, these preferences are used _during_ automatic path attribution.

#### magic behavior

an agreement to review path `/` will accept all automatic path attributions, the same behavior will be enforced when blacklisting
paths for consistency
