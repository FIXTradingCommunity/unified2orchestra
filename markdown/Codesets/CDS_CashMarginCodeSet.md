### Codeset CashMarginCodeSet type char (544)

Identifies whether an order is a margin order or a non-margin order. This is primarily used when sending orders to Japanese exchanges to indicate sell margin or buy to cover. The same tag could be assigned also by buy-side to indicate the intent to sell or buy margin and the sell-side to accept or reject (base on some validation criteria) the margin request.

| Name        | Value | Id     | Sort | Synopsis     |
|-------------|-------|--------|------|--------------|
| Cash        | 1     | 544001 | 1    | Cash         |
| MarginOpen  | 2     | 544002 | 2    | Margin Open  |
| MarginClose | 3     | 544003 | 3    | Margin Close |

