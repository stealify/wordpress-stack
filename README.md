# wordpress-stack
Diffrent wordpress Hosting Solutions Written in ECMAScript but deployable to any PHP Hosting.

## Why?
Wordpress is still one of the most wide used CMS Systems and is trying hard to make the transition into a NodeJS Based CMS that is deployable to PHP Environments
the user interface concepts and conventions are well known by millions of Developers around the world. 

builds a good entrypoint for Wordpress / PHP / Laravel and so on

also using php workers is a good scaleable way to query mysql and cache the query computation in with the excelent php cache. if you did not implement something better in your NodeJS or stealify App then this is also a good quickstart while the stack does not scale well with millions of users concurrently that is a issue that most people will never face as they never reach that scale of concurrent data access and writes.

it is relativ easy to transform the stack incremental because of the ability to use a loadbalancer as splitting point and also ingest the php output.
