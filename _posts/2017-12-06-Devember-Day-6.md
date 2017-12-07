---
published: true
---

## Ruby Ruby Ruby Ruby, Ruby Over Here!

Suddenly rake is no longer working and my env is toast...reinstalling with an older version of ruby in hopes it'll fix some of the problems. Definitely not impressed by the OSS repo I'm using, but leaning towards just rolling my own from scratch if this continues. Fixed! Seems my gem cache was foobar'd.

	bundle exec bundle install --path vendor/cache
