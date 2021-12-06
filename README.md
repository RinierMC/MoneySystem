# MoneySystem
Adds Economy on your server
# Api
First Put:
```php
$money =Server::getInstance()->getPluginManager()->getPlugin("MoneySystem");
```

To add money to a player use
```php
$money->addMoney($player, $amount);
```

To remove money to a player use
```php
$money->removeMoney($player, $amount);
```

# Commands
/money|add|remove|player|amount
|:--:|:--:|:--:|:--:|:--:|
