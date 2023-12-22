# Reproducer "Live Action Redirect"

## Install

```
composer install
```

## Run

```
symfony serve 
symfony open:local
```

## Reproduce

1. Open the page "/"
2. Click on the button "LiveAction foo()"
3. The page is redirected to the page "/bar"
