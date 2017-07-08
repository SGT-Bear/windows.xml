			<!-- Begin Food & Water Mod -->
			
			<rect width="168" height="43" controller="HUDStatBar" stat_type="Food" visible="{statvisible}">
				<sprite depth="1" name="border" color="0,0,0,100" height="43" type="sliced"/>
				<sprite depth="2" pos="3,-3"  name="background" height="37" width="162" color="64,64,64,100" type="sliced" />
				<sprite depth="3" pos="3,-3"  name="BarContent" type="filled" height="37" width="162" color="0,128,0,100" fill="0"  />
				<sprite depth="4" name="Icon" atlas="{staticonatlas|once}" sprite="{staticon|once}" size="32,32" pos="8,-6" foregroundlayer="true"/>
				<label depth="6" name="TextContent" pos="0,-8" font_size="28" color="[white]" justify="center" pivot="topleft" text="{statcurrentwithmax}" height="30"/>
			</rect>

			<rect width="168" height="43" controller="HUDStatBar" stat_type="Water" visible="{statvisible}">
				<sprite depth="1" name="border" color="0,0,0,100" height="43" type="sliced"/>
				<sprite depth="2" pos="3,-3"  name="background" height="37" width="162" color="64,64,64,100" type="sliced" />
				<sprite depth="3" pos="3,-3"  name="BarContent" type="filled" height="37" width="162" color="0,153,255,100" fill="0"  />
				<sprite depth="4" name="Icon" atlas="{staticonatlas|once}" sprite="{staticon|once}" size="32,32" pos="8,-6" foregroundlayer="true"/>
				<label depth="6" name="TextContent" pos="0,-8" font_size="28" color="[white]" justify="center" pivot="topleft" text="{statcurrentwithmax}" height="30"/>
			</rect>
			
			
			<!-- End Food & Water Mod -->
		</grid>
		
			<!-- Begin Player Core Temp Mod -->
			
		<grid name="hud" pos="187,52" rows="1" cols="1" width="168" cell_width="168" cell_height="46" repeat_content="false" controller="InGameHUD" side="left" >
			<rect width="168" height="43" controller="PlayerStatsWindow">
				<sprite depth="1" name="border" color="0,0,0,100" height="43" type="sliced"/>
				<sprite depth="2" pos="3,-3"  name="background" height="37" width="162" color="64,64,64,100" type="sliced"/>
				<sprite depth="3" pos="3,-3"  color="50,50,50" type="filled" height="37" width="162" fill="100" />
				<sprite depth="4" name="Icon" sprite="ui_game_symbol_temperature" size="32,32" pos="8,-6" foregroundlayer="true"/>
				<label depth="6" name="TextContent" pos="0,-10" font_size="24" color="[beige]" justify="center" pivot="topleft" text="{playercoretemp}" height="30" />
			</rect>
		</grid>
			
			<!-- Begin Player Core Temp Mod -->
