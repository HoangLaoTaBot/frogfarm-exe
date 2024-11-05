# Hướng dẫn cấu hình file config.json
| TỪ KHÓA   | GIÁ TRỊ      | Ý NGHĨA                                                                    |
|-----------|--------------|----------------------------------------------------------------------------|
| AUTO_TASK | true / false | ( On / Off ) Tính năng làm nhiệm vụ                                        |
| AUTO_PUZZLE | true / false | ( On / Off ) Tính năng nhặt puzzle                                         |
| AUTO_GET_NEW_QUERY_ID | true / false | ( On / Off ) Tính năng tự động mở hidemium để lấy query_id mới khi hết hạn              |
| AUTO_WRITE_ERROR | true / false | ( On / Off ) Tính năng ghi log lỗi ra file error.txt                                    |
| AUTO_SEND_ERROR_TELEGRAM | true / false | ( On / Off ) Tính năng gửi thông báo lỗi sang telegram channel                          |
| AUTO_SEND_TELEGRAM_LOGOUT | true / false | ( On / Off ) Tính năng gửi thông báo tài khoản telegram bị logout sang telegram channel |
| USER_AGENT |  | User agent fake thông tin thiết bị                                                      |
| AUTO_STOP_PROCESS | true / false | ( On / Off ) Tính năng tự động dừng script khi call API lỗi quá 10 lần                  |
| IS_CHECK_QUERY_ID | true / false | ( On / Off ) Tính năng kiểm tra query_id còn hạn không                                  |
| NUMBER_TRY_REQUEST | 3            | Số lần thử call lại API khi lỗi                                                         |
| THREAD | 10           | Số luồng chạy đồng thời cùng lúc                                                        |
| IS_SLEEP | 27500        | Số thời gian đợi chạy vòng lặp mới ( giây )                                             |
| BOT_TOKEN |              | Token của bot telegram channel                                                          |
| BOT_CHANNEL_ID |              | ID của telegram channel                                                                 |
| BOT_TOKEN_LOGOUT |              | Token của bot telegram channel                                                          |
| BOT_CHANNEL_ID_LOGOUT |              | ID của telegram channel                                                                 |
| BOT_NAME_GAME | Frog Farm    | Tên game                                                                   |
