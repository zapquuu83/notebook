###Welcome to use MarkDown
<!--table标签-->
		<!--4行3列的表格-->
		<!--table
			width 宽度 固定值 百分比
			height 高度
			border 边框
			align 对齐方式 left center right
			cellspacing 单元格和单元格的间隙
			cellpadding 文字边框的距离
			合并列colspan
			合并行rowspan
			bgcolor 背景色
			background 背景图
		-->
		<!--不管合并与否，一定要保证每一行的td数量必须是一致列的合并
			1.先找到要合并的最左边的单元格
			2.家colspan属性，值是被合并的单元格个数
			3.吧被合并的单元格删除或注释
			行的合并
			1,。先找到要合并的最左边的单元格
			2.加rowspan属性，值是被合并的单元格个数
			3.把被合并的单元格删除或注释
			列和行的合并
			1.
		-->
		<table width="90%" height="50%" border="1" cellspacing="0" cellpadding="10">
			<tr align="center" bgcolor="antiquewhite">
				<td colspan="2" rowspan="2">1</td>
				<!--<td>2</td>
				<td>3</td>-->
			</tr>
			<tr>
				<td></td>
				<td></td>
				<td></td>
			</tr>
			<tr>
				<td></td>
				<td></td>
				<td></td>
			</tr>
			<tr>
				<td></td>
				<td></td>
				<td></td>
			</tr>
		</table>
		<table cellpadding="0" cellspacing="10px" border="1">
			<tr>
				<td>1</td>
				<td>2</td>
				<td>3</td>
			</tr>
			<tr>
				<td></td>
				<td></td>
				<td></td>
			</tr><tr>
				<td></td>
				<td></td>
				<td></td>
			</tr>
		</table>
		table>tr*3>td{单元格$}[align="center" color"red"]