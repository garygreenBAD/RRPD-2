#### Roadmap based on T-Shirt sizes

If you've T-Shirt sized your Epics, then you need a way to convert that to a value.  We've had considerable success using an enhanced version of Fibonacci first:

|T-Shirt| Points |
|:-----:|:------:|
| XS    | 10     |
| S     | 30     |
| M     | 80     |
| L     | 210    |
| XL    | 550    |

It's essentially the Fibonacci sequent x 10 and skipping every other number.  The reason to do this is to enhance the Fibonacci effect and force larger Epics to be scary and need breaking down.

In order to produce a release roadmap, we need to attempt to estimate Epic delivery velocity.  For new teams, this can be challenging.  Our normal rule of thumb is one of the following:

- Model based on an average of other team(s) velocity
- Get the team to deliver some prototypes or proofs of concepts in earlier phases and use that to model velocity.  This is especially important for new teams, new technologies or large scale projects
- The last resort it to be honest and agree an initial velocity and review once you've delivered a few increments

>**Warning:** There be dragons here - It's best to be honest that the plan is draft and needs empirical data (e.g.; increments) to validate it and it will change.  We usually ask for 1-3 months to validate the plan.

Ultimately software delivery is not predictable; the process is, the outcome is not.  The Cone of Uncertainty shows us, we could be significantly out on our early estimates.  Blended Agile Delivery aims to minimise this by mitigating risks early in the process, delivering a number of small increments to validate our pace and estimate variability.
