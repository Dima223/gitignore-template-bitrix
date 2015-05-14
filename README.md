# .gitignore-template-bitrix
Шаблон `.gitignore` для 1С-Битрикс

```
### bitrix development template

# bitrix kernel dir
/bitrix/

# bitrix upload dir
/upload/

# bitrix service scripts
/bitrix_setup.php
/restore.php
/bitrix_server_test.php

# dir configuration for apache
/.htaccess

# seo staff
/*sitemap*.xml
/robots.txt

## without local
# !/bitrix/
# /bitrix/*
# !/bitrix/templates/

# archives
*.gz
.gz.
*.tar
.tar.
*.rar
*.zip
*.7z
*.bz
.bz.

# PhpStorm ide
.idea/
```
