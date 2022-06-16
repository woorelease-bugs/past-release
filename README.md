# Test repo for [woorelease](https://github.com/woocommerce/woorelease)
You cannot get any changelog entries for a past release

1. Release `1.0.0` (manually, as you [cannot do that with the woorelease either](https://github.com/woorelease-bugs/initial-release))
2. Marge a few PRs
3. Release `1.0.1`
	```
	= 1.0.1 - 2022-06-16 =
	* Add - a workflow to attach label based on PR branchname.
	* Add - release.yml.
	```
5. Try to re-generate changelog for the 1.0.1 again
	```
	woorelease cl:generate --product_version=1.0.1 https://github.com/woorelease-bugs/before-tag-time/tree/develop
	```	
	```
	= 1.0.1 - 2022-06-16 =
	```

## Prerequisites

We aim to support the latest two minor versions of WordPress, WooCommerce, and PHP. (L-2 policy)

-   WordPress 5.7+
-   WooCommerce 6.0+
-   PHP 7.3+

<p align="center">
	<br/><br/>
	Made with 💜 by <a href="https://woocommerce.com/">WooCommerce</a>.<br/>
	<a href="https://woocommerce.com/careers/">We're hiring</a>! Come work with us!
</p>
