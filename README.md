# SPiD JS SDK

SDK to integrate to the SPiD frontend API.
Used to check if user is logged in or not, or owns a product or not.

## Documentation

Documentation is available on http://techdocs.spid.no/sdks/javascript/
and make sure to read the API docs http://techdocs.spid.no/sdks/js/api-docs/.

## Release

Bump [Semver](http://semver.org/) version with this command  

`$ npm version <patch | minor | major>`  

`$ npm publish`  

Do a release on Github with the built files.  
Upload built files to CDN bucket.  

## Notes

All versions of the SDK will use a global variable/namespace&mdash;`SPiD.Talk.response`&mdash;when making JSONP calls.
This may change at a later date.
