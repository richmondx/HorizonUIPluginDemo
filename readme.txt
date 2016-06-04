

example 1: rich text simple

<text color="#77FF77AA" shadowColor="#FF0000FF" shadowOffset="[4,3]">This is rich text simple test:</text>
<br/>
<text color="#FF0000AA">This is strawberry:</text><img filePath="Texture2D'/Game/Item/I_C_Strawberry.I_C_Strawberry'" size="[100, 100]" /><br/>
<text color="#0000FFFF">This is Watermellon:</text><img color="#FF00FF77" filePath="/Game/Item/I_C_Watermellon" size="[100, 100]" /> <br/>
<text color="#FFFF00FF">This is animated man using material:</text><img filePath="Material'/Game/Material/mat_flipbook.mat_flipbook'" size="[100, 100]" /> <br/>


note: both Texture2D'/Game/Item/I_C_Strawberry.I_C_Strawberry' and  /Game/Item/I_C_Strawberry.I_C_Strawberry can work correctly

example 2: rich text font
<text>This is Default Font</text><br/>
<text fontPath="/Engine/EngineFonts/Roboto" fontType="Regular" fontSize="30">This is Roboto Regular fontSize=30</text><br/>
<text fontPath="/Engine/EngineFonts/Roboto" fontType="Italic" color="#FF0000AA">This is Roboto Italic</text><br/>
<text fontPath="/Engine/EngineFonts/Roboto" fontType="Bold Italic"  fontSize="40" color="#FF3366AA">This is Roboto Bold Italic fontSize=40</text><br/>
<text fontPath="/Engine/EngineFonts/Roboto" fontType="Light" color="#FFFF00AA">This is Roboto Light</text><br/>
<text fontPath="/Engine/EngineFonts/RobotoTiny" fontType="Light" color="#FF0A40AA">This is RobotoTinyLight</text><br/>



example 3: padding

<text fontSize="55">Test case:</text> 
<text padding-right="5" padding-top="20">
 <text padding-left="5">padding text block</text>
 <img filePath="/Game/Material/mat_flipbook"/>
 <img filePath="/Game/Item/I_C_Watermellon" size="[100,100]" />
</text>
<text>after padding</text>