# dotfiles

Meus atalhos de teclado (layout `us(intl)` customizado para escrever em português).

## Como funciona
- **Caps Lock** vira o AltGr: `Caps + E` = `é`, `Caps + C` = `ç`, `Caps + A` = `á`.
- **Ctrl direito** é o seletor extra: `Ctrl dir + E` = `ê`, `A` = `ã`, `O` = `õ`.
  Com Caps junto: `è`, `â`, `ô`.

## Instalar
```bash
git clone https://github.com/Momas7/dotfiles ~/dotfiles
~/dotfiles/scripts/setup-keyboard.sh
```
Depois faça logout/login e escolha `English (US, intl., with dead keys)`.

## Modificar
Edite `dotconfig/keyboard`. Cada linha é `key <CÓDIGO> { [ normal, shift, altgr, altgr+shift, ... ] };`
e rode o script de novo.

Baseado em https://github.com/EuCaue/dotfiles
