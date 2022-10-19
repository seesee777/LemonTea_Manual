## Tea Stove：

### How to

Small·Tea Stove

![how to use tea stove](../../mc_icon/tea_room/tea_stove.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove.gif">)

Large·Tea Stove

![how to use tea stove large](../../mc_icon/tea_room/tea_stove_large.gif)

[//]: # (<img src="./mc_icon/tea_room/tea_stove_large.gif">)

* Steps
  * Put a book in the first slot of the container
  * Drop a consumable over the container
  * Players must be within 5 blocks of the consumable

[Tea Recipe](/en_us/tea_room/tea_recipe.md)

### Container

<table>
	<tablebody>
		<tr>
			<td>Container</td>
			<td>Container ID</td>
			<td>ItemPosition</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/barrel.png">Barrel</td>
			<td>barrel</td>
			<td rowspan="4"><img src="./mc_icon/tea_room/pos_barrel.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/shulker_box/shulker_box.png">Shulker Box</td>
			<td>shulker_box</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/chest.png">Chest</td>
			<td>chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/trapped_chest.png">Trapped Chest</td>
			<td>trapped_chest</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/large_chest.png">Large Chest</td>
			<td>large_chest</td>
			<td><img src="./mc_icon/tea_room/pos_large_chest.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/hopper.png">Hopper</td>
			<td>hopper</td>
			<td><img src="./mc_icon/tea_room/pos_item_hopper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dropper.png">Dropper</td>
			<td>dropper</td>
			<td rowspan="2"><img src="./mc_icon/tea_room/pos_dropper.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/redstone/dispenser.png">Dispenser</td>
			<td>dispenser</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/furnace.png">Furnace</td>
			<td>furnace</td>
			<td rowspan="3"><img src="./mc_icon/tea_room/pos_furnace.png"></td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/blast_furnace.png">Blast Furnace</td>
			<td>blast_furnace</td>
		</tr>
		<tr>
            <td><img src="./mc_icon/decorations/smoker.png">Smoker</td>
			<td>smoker</td>
		</tr>
	</tablebody>
</table>

### Hint

* Detect spatial order
   * First detect the container in the block where the consumable is located, such as chest, hopper and other incomplete blocks.
   * Then check the container in the block below the consumable, such as barrel, shulker box and other complete blocks.

* Detect time sequence
   * Detected every 20ticks, the detection of different items is staggered.




