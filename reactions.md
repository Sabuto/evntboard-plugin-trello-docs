# Reactions

## getBoard

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| boardName  | string  | :heavy_check_mark:  | none  | Name of the board to retrieve  |

```
module.exports = async (data, services) => {
  await services.plugin('trello', 'getBoard', 'Board Name')
}
```

## addCard

Allows you to add a card to a list on a board

| Field  | Type  | Required  | Default  | Description  |
|---|---|---|---|---|
| boardName  | string  | :heavy_check_mark:  | none  | Name of the board to add the card  |
| list | string | :heavy_check_mark: | none | Name of the list on that board to add to |
| name | string | :heavy_check_mark: | none | The name of the card |
| desc | string | :heavy_check_mark: | none | The description to put in the card |
