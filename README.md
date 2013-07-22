# Empty Extension for kickstarting FluidTYPO3 based Projects

This extension provides the minimal Setup needed for using the FluidTYPO3 extensions
for your own project.

## How to go on from here?

You should do the follwing:

-	git clone / install the extension to your TYPO3 Dev environment
-	create a copy for your project (**inside typo3conf/ext**) named for example **my_ext**
-	do your work inside ``my_ext``
-	adjust ``ext_emconf.php`` and ``ext_tables.php`` to your needs (be aware of changing only
	parts known to you or the most obvious such as description, TypoScript inclusion text..
-	adjust ``Configuration/TypoScript/setup.txt`` and ``Configuration/TypoScript/constants.txt``
	to reflect your extension key. It is always prefixed with ``tx_`` and per convention
	contains no underscore. ``my_ext`` would therefore result in ``tx_myext``
-	install your extension locally via the Extension Manager **after** modifying the above mentioned
