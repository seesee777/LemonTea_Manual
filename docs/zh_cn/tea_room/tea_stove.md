## 茶炉：

### 用法

小·茶炉

![how to use tea stove](../../mc_icon/tea_room/tea_stove.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove.gif">)

大·茶炉

![how to use tea stove large](../../mc_icon/tea_room/tea_stove_large.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove_large.gif">)

* 步骤
  * 将一本书放到容器中第一格
  * 将一个消耗品扔在容器上方
  * 玩家距离消耗品5格之内

[茶方](/zh_cn/tea_room/tea_recipe.md)

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
            <td><img src="./mc_icon/decorations/shulker_box/shulker_box.png">潜影盒</td>
			<td>shulker_box</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/chest.png">箱子</td>
			<td>chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/trapped_chest.png">陷阱箱</td>
			<td>trapped_chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/large_chest.png">大箱子</td>
			<td>large_chest</td>
			<td><img src="./mc_icon/tea_room/pos_large_chest.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/hopper.png">漏斗</td>
			<td>hopper</td>
			<td><img src="./mc_icon/tea_room/pos_item_hopper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dropper.png">投掷器</td>
			<td>dropper</td>
			<td rowspan="2"><img src="./mc_icon/tea_room/pos_dropper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dispenser.png">发射器</td>
			<td>dispenser</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/furnace.png">熔炉</td>
			<td>furnace</td>
			<td rowspan="3"><img src="./mc_icon/tea_room/pos_furnace.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/blast_furnace.png">高炉</td>
			<td>blast_furnace</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/smoker.png">烟熏炉</td>
			<td>smoker</td>
		</tr>
	</tablebody>
</table>

### 提示



* 检测空间顺序
  * 首先检测消耗品所在方块内的容器，如箱子、漏斗等不完整方块
  * 然后检查消耗品下方方块内的容器，如木桶、潜影盒等完整方块

* 检测时间顺序
  * 每间隔20ticks检测一次，对不同物品的检测是错峰的。


