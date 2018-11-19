# SELECTOR

各種狀況變換圖片的 SELECTOR

android：state_enabled：設置觸摸或點擊事件是否可用狀態，一般只在假時設置該屬性，表示不可用狀態

android：state_pressed：設置是否按壓狀態，一般在true時設​​置該屬性，表示已按壓狀態，默認為false

android：state_selected：設置是否選中狀態，true表示已選中，false表示未選中

android：state_checked：設置是否勾選狀態，主要用於CheckBox和RadioButton，true表示已被勾選，false表示未被勾選

android：state_checkable：設置勾選是否可用狀態，類似state_enabled，只是state_enabled會影響觸摸或點擊事件，而state_checkable影響勾選事件

android：state_focused：設置是否獲得焦點狀態，true表示獲得焦點，默認為false，表示未獲得焦點

android：state_window_focused：設置當前窗口是否獲得焦點狀態，true表示獲得焦點，false表示未獲得焦點，例如拉下通知欄或彈出對話框時，當前界面就會失去焦點;另外，ListView的ListItem獲得焦點時也會觸發真正的狀態，可以理解為當前窗口就是列表項本身

android：state_activated：設置是否被激活狀態，真表示被激活，虛表示未激活，API Level 11及以上才支持，可通過代碼調用控件的setActivated（boolean）方法設置是否激活該控件

android：state_hovered：設置是否鼠標在上面滑動的狀態，真表示鼠標在上面滑動，默認為false，API等級14及以上才支持

參考：https://developer.android.com/guide/topics/resources/color-list-resource
