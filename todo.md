- get: retrieve
- post: add a resource
- put: replace a resource
- patch: update part of a resource
- remove: remove a resource

`php artisan make:controller PostController --resource` creates app/Http/Controllers/PostController

build responses
- message (success for failure)
- data (optional)
- link (optional link to related resources)