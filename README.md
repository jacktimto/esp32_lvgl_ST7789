copy from https://gitee.com/caidamao/key_-esp32


# esp32_lvgl_ST7789
develop esp32 with lvgl st7789 driver

# edit pin
edit spi pin   in /component/user_dev/SPI/User_dev_spi.h  
edit other pin  in /component/user_mid/User_mid_LCD.h  

# 屏幕实现
屏幕实现 在LV_GUI_APP.C  下的void lvgl_task(void *arg);  
添加组件需要修改  /lvgl/lv_conf.h  

# 尝试移植LVGL9
TBD  
