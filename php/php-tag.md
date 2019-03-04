# PHP Opening Tag

Only use `<?php` and `<?=` tags, do not use the `<?` shorthand. This is the most portable way to include PHP code on differing operating systems and setups.

Replace the `?>` with `//eof` if the file contains only PHP code (not embedded into HTML) To avoid risking to have whitespaces after the closing tag which may stop headers to work.
