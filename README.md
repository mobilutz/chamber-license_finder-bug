# Chamber and LicenseFinder problem

https://github.com/thekompanee/chamber/issues/73

These two gem, in their most current version do not work together.

When running `bundle install` this is the error I am getting:

```
Fetching gem metadata from https://rubygems.org/............
Fetching gem metadata from https://rubygems.org/.
Resolving dependencies...
Bundler could not find compatible versions for gem "thor":
  In Gemfile:
    chamber (~> 2.13.1) was resolved to 2.13.1, which depends on
      thor (>= 0.19.1, < 0.21)

    license_finder (> 6.0) was resolved to 6.8.2, which depends on
      thor (~> 1.0.1)
```
