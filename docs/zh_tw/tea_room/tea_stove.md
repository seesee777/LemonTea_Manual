## 茶爐：

### 用法

小·茶爐

![how to use tea stove](../../mc_icon/tea_room/tea_stove.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove.gif">)

大·茶爐

![how to use tea stove large](../../mc_icon/tea_room/tea_stove_large.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove_large.gif">)

* 步驟
  * 將一本書放到容器中第一格
  * 將一個消耗品扔在容器上方
  * 玩家必須距離消耗品5格之內

[茶方](/zh_tw/tea_room/tea_recipe.md)

### 容器

<table>
	<tablebody>
		<tr>
			<td>容器</td>
			<td>容器 ID</td>
			<td>物品位置</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/barrel.png">木桶</td>
			<td>barrel</td>
			<td rowspan="4"><img src="./mc_icon/tea_room/pos_barrel.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/shulker_box/shulker_box.png">界伏盒</td>
			<td>shulker_box</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/chest.png">儲物箱</td>
			<td>chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/trapped_chest.png">陷阱儲物箱</td>
			<td>trapped_chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/large_chest.png">大型儲物箱</td>
			<td>large_chest</td>
			<td><img src="./mc_icon/tea_room/pos_large_chest.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/hopper.png">漏斗</td>
			<td>hopper</td>
			<td><img src="./mc_icon/tea_room/pos_item_hopper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dropper.png">投擲器</td>
			<td>dropper</td>
			<td rowspan="2"><img src="./mc_icon/tea_room/pos_dropper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dispenser.png">發射器</td>
			<td>dispenser</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/furnace.png">熔爐</td>
			<td>furnace</td>
			<td rowspan="3"><img src="./mc_icon/tea_room/pos_furnace.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/blast_furnace.png">高爐</td>
			<td>blast_furnace</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/smoker.png">煙燻爐</td>
			<td>smoker</td>
		</tr>
	</tablebody>
</table>

### 提示





* 檢測空間順序
  * 首先檢測消耗品所在方塊內的容器，如箱子、漏斗等不完整方塊。
  * 然後檢查消耗品下方方塊內的容器，如木桶、潛影盒等完整方塊。

* 檢測時間順序
  * 每間隔20ticks檢測一次，對不同物品的檢測是錯峰的。