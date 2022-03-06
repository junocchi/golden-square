# Setting Up RSpec

_[A video demonstration is here.](https://www.youtube.com/watch?v=wHkVhq5R0_8&t=600s)_

Learn to set up a new RSpec project.

## Guidance

RSpec is a kind of programming tool called a test framework. It is written for
use with the programming language Ruby. We can use it to test that our systems
do what they are supposed to do. We can also use it to build our test-driving
practice.

To set up a new RSpec project:

```shell
# This assumes you have Ruby & RVM installed. If you don't, visit:
# https://rvm.io/ to install RVM.

# First we're going to get you the latest Ruby
; rvm get stable
; rvm use ruby --latest --install --default

# Next, install bundler, which manages dependencies like RSpec
; gem install bundler

# Create a bundler project
; bundle init

# And add RSpec to your dependencies
; bundle add rspec

# Generate an RSpec template
; rspec --init

# And create a repository for your changes
; git init .
; git add .
; git commit -m "Project setup"

# Then go and create a repository on github.com
# And follow the "Push an existing repository from the command line" section
# To push your project to your github repository
# It will look something like this...
; git remote add origin YOUR_REMOTE_ADDRESS
; git branch -M main
; git push -u origin main
```


<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/golden-square&prefill_File=pills/setting_up_an_rspec_project.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/golden-square&prefill_File=pills/setting_up_an_rspec_project.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/golden-square&prefill_File=pills/setting_up_an_rspec_project.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/golden-square&prefill_File=pills/setting_up_an_rspec_project.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy/golden-square&prefill_File=pills/setting_up_an_rspec_project.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->