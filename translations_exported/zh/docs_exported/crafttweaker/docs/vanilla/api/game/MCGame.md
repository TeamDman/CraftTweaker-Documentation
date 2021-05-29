# MCGame

Holds general game information. Can be accessed using the `game` global keyword

## 导入相关包

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.game.MCGame;
```


## 方法

:::group{name=localize}



Return Type: string

```zenscript
// MCGame.localize(translationKey as string) as string

game.localize("gui.up");
```

| 参数             | 类型     | 描述                      |
| -------------- | ------ | ----------------------- |
| translationKey | string | No Description Provided |


:::


## 参数

| 名称                    | 类型                                                                                                 | 可获得  | 可设置   | 描述                      |
| --------------------- | -------------------------------------------------------------------------------------------------- | ---- | ----- | ----------------------- |
| blockStates           | Collection&lt;[MCBlockState](/vanilla/api/block/MCBlockState)&gt;                      | true | false | No Description Provided |
| blocks                | Collection&lt;[MCBlock](/vanilla/api/block/MCBlock)&gt;                                | true | false | No Description Provided |
| directionAxises       | Collection&lt;[DirectionAxis](/vanilla/api/util/DirectionAxis)&gt;                     | true | false | No Description Provided |
| effects               | Collection&lt;[MCPotionEffect](/vanilla/api/potions/MCPotionEffect)&gt;                | true | false | No Description Provided |
| entityClassifications | Collection&lt;[MCEntityClassification](/vanilla/api/entity/MCEntityClassification)&gt; | true | false | No Description Provided |
| entityTypes           | Collection&lt;[MCEntityType](/vanilla/api/entities/MCEntityType)&gt;                   | true | false | No Description Provided |
| fluids                | Collection&lt;[MCFluid](/vanilla/api/fluid/MCFluid)&gt;                                | true | false | No Description Provided |
| formattings           | Collection&lt;[TextFormatting](/vanilla/api/util/text/TextFormatting)&gt;              | true | false | No Description Provided |
| items                 | Collection&lt;[IItemStack](/vanilla/api/items/IItemStack)&gt;                          | true | false | No Description Provided |
| potions               | Collection&lt;[MCPotion](/vanilla/api/potions/MCPotion)&gt;                            | true | false | No Description Provided |
| recipeTypes           | Collection&lt;[IRecipeManager](/vanilla/api/managers/IRecipeManager)&gt;               | true | false | No Description Provided |
