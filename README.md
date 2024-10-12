# report

rg --no-heading "echo.*\\\$_GET" | grep "\.php:" | grep -v -e "(\$_GET" -e "( \$_GET" -e "esc_" -e "admin_url" -e "(int)" -e htmlentities
