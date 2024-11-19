Paradox Interactive启动器在部分设备上无法使用

可能因为Windows版本

无法启动启动器可能导致无法修改语言

需要修改 "用户名/Documents/Paradox Interactive/Hearts of Iron IV" 中的pdx_settings.txt修改为

pdx_settings.txt内

"System"=

{

	"language"=
 
        {
  
		value="语言"
  
		version=0
  
	}
 
}

将value＝"language"修改为想要的语言
