# Twitch Provider

## Installation

```
composer require socialite-manager/twitch-provider
```

## Usage

```php
use Socialite\Provider\TwitchProvider;
use Socialite\Socialite;

Socialite::driver(TwitchProvider::class, $config);
```
