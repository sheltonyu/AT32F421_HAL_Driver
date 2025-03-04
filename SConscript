from building import *
import os

cwd = GetCurrentDir()
path = [os.path.join(cwd, 'inc')]
src_path = os.path.join(cwd, 'src')

CPPDEFINES = ['USE_STDPERIPH_DRIVER']

src = [
os.path.join(src_path, 'at32f421_adc.c'),
os.path.join(src_path, 'at32f421_cmp.c'),
os.path.join(src_path, 'at32f421_crc.c'),
os.path.join(src_path, 'at32f421_crm.c'),
os.path.join(src_path, 'at32f421_debug.c'),
os.path.join(src_path, 'at32f421_dma.c'),
os.path.join(src_path, 'at32f421_ertc.c'),
os.path.join(src_path, 'at32f421_exint.c'),
os.path.join(src_path, 'at32f421_flash.c'),
os.path.join(src_path, 'at32f421_gpio.c'),
os.path.join(src_path, 'at32f421_i2c.c'),
os.path.join(src_path, 'at32f421_misc.c'),
os.path.join(src_path, 'at32f421_pwc.c'),
os.path.join(src_path, 'at32f421_scfg.c'),
os.path.join(src_path, 'at32f421_spi.c'),
os.path.join(src_path, 'at32f421_tmr.c'),
os.path.join(src_path, 'at32f421_usart.c'),
os.path.join(src_path, 'at32f421_wdt.c'),
os.path.join(src_path, 'at32f421_wwdt.c'),
]

group = DefineGroup('libraries', src, depend = ['PKG_USING_AT32F421_HAL_DRIVER'], CPPPATH = path, CPPDEFINES = CPPDEFINES)

Return('group')
