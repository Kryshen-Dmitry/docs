# Pl-Checkbox
Чекбокс представляет собой выбор одного или нескольких значений для пользователя

<pl-checkbox label="Чекбокс" orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Чекбокс" orientation="horizontal"></pl-checkbox>
</details>

## Examples

### Orientation
Используйте `orientation` для изменения расположения текста

<pl-checkbox label="horizontal orientation" orientation="horizontal"></pl-checkbox>
<br>
<pl-checkbox label="vertical orientation" orientation="vertical"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="horizontal orientation" orientation="horizontal"></pl-checkbox>

    <pl-checkbox label="vertical orientation" orientation="vertical"></pl-checkbox>
</details>

### Caption
Используйте `caption` что бы добавить дополнительную подпись справа от чекбокса

<pl-checkbox label="label" caption="caption" orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="horizontal orientation" orientation="horizontal"></pl-checkbox>

    <pl-checkbox label="vertical orientation" orientation="vertical"></pl-checkbox>
</details>

### Disabled
Используйте `disabled` что бы сделать чекбокс не активным

<pl-checkbox label="Текст" disabled orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Текст" disabled orientation="horizontal"></pl-checkbox>
</details>

### Hidden
Используйте `hidden` что бы не отображать чек бокс

<pl-checkbox label="Текст" hidden orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Текст" hidden orientation="horizontal"></pl-checkbox>
</details>

### Readonly
Используйте `readonly` что бы запретить изменять значение чекбокса

<pl-checkbox label="Текст" readonly orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Текст" readonly orientation="horizontal"></pl-checkbox>
</details>

### Сhecked
Используйте `checked` что бы сделать чекбокс по умолчанию активным

<pl-checkbox label="Текст" checked orientation="horizontal"></pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Текст" checked orientation="horizontal"></pl-checkbox>
</details>

### Slots
Используйте `label-prefix` или `label-suffix` для того что бы добавить иконку к подписи

<pl-checkbox label="Текст" label-width="60" orientation="horizontal">
    <pl-icon slot="label-prefix" variant="primary" iconset="pl-default" size="16" icon="settings"></pl-icon>
</pl-checkbox>
<br>
<pl-checkbox label="Текст" label-width="60" orientation="horizontal">
    <pl-icon slot="label-suffix" variant="primary" iconset="pl-default" size="16" icon="settings"></pl-icon>
</pl-checkbox>

<details>
    <summary>html</summary>

    <pl-checkbox label="Текст" label-width="60" orientation="horizontal">
        <pl-icon slot="label-prefix" variant="primary" iconset="pl-default" size="16" icon="settings"></pl-icon>
    </pl-checkbox>

    <pl-checkbox label="Текст" label-width="60" orientation="horizontal">
        <pl-icon slot="label-suffix" variant="primary" iconset="pl-default" size="16" icon="settings"></pl-icon>
    </pl-checkbox>
</details>


## Properties

| Name  | Description  | ReflectsToAttribute | Type | Default
|---|---|:----:|---|:---:|
| `label` | Подпись  | - | `string` |  (empty)
| `orientation` | Расположение подписи относительно текстового поля | - | `horizontal \| vertical` | `vertical`
| `caption` | ...  |  + | `string` | `false`
| `disabled` | ...  |  + | `string` | `false`
| `hidden` | ...  |  + | `string` | `false`
| `readonly` | ...  |  + | `string` | `false`
| `checked` | ...  |  - | `string` | `false`


## Slots

| Name  | Description  
|---|---
| `label-prefix` | Слот для префикса подписи поля ввода, значки располагаются перед подписью
| `label-suffix` | Слот для суфикса подписи поля ввода, значки располагаются после подписи
