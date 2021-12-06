# MoneySystem
Adds Economy on your server
# Add This On Your Code:
```php
$money =Server::getInstance()->getPluginManager()->getPlugin("MoneySystem");
```

# Adding money to a player
```php
$money->addMoney($player, $amount);
```

# Removing money to a player
```php
$money->removeMoney($player, $amount);
```

# Getting Player's Money
```php
$money->getMoney($player, $amount);
```

# Commands
Add/Remove Command

`
/money <add|remove> <player> <amount>
`

Pay Command

`
/pay <player> <amount>
`

Top Command

`
/topmoney
`

My Money Command

`
/mymoney
`

# Permissions
Add Money Permission

`
money.add.command
`

Remove Momey Permission

`
money.remove.command
`


