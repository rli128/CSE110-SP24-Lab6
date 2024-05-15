1. Where would you fit your automated tests in your Recipe project development pipeline?

    Within a Github action that runs whenever code is pushed - We need to be able to automatically check code whenever it is pushed so that we can check early whether there are bugs in the code branch so we don't corrupt the main code. This is best to implement in Github actions so we don't need to manually check our code every single time we try to push.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

    No, end-to-end testing is for testing user-interaction


