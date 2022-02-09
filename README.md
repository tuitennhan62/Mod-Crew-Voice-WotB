# Mod-Crew-Voice-WotB

Mã nguồn của dự án WWISE để tạo ra phần tiếng kíp lái cho game

Dự án này sẽ giúp bạn tự chỉnh sửa tiếng kíp lái cho game World of Tanks Blitz bằng cách sử dụng Audiokinetic WWISE

Dự án WWISE này hoạt động ổn định với phiên bản: 2019.2.9.7459 
# Video hướng dẫn
K-2 WotB: https://youtu.be/hoVZxmDLQ5M
 
Lakia_Max https://youtu.be/4JT-XhLhToo
# Hướng Dẫn

Bước 1: Tạo tài khoản Audiokinetic

Bước 2: Vào trang chủ của Audiokinetic, Tải về Wwise Laucher

Bước 3 : Cài đặt

Bước 4: Mở và đăng nhập

Bước 5: Ở App Wwise Laucher, Chọn "Wwise" 
(hàng thứ 2 bên trái)

Bước 6: Ở bên phải của "All" sửa 2022.2 thành 2019.2

Bước 7: Ở bên phải của 2019.2, chọn phiên bản WWISE 2019.2.9.7459

Bước 8: Sau khi chọn phiên bản, ấn "Install"

Bước 9: Sau khi cài đặt, hãy mở thư mục "Download" trong File Explorer

Bước 10: Giải nén tất cả Project WWISE VOICE WOT BLITZ (muốn giải nén ở đâu cũng được)

Bước 11: Mở tệp Project WotB Wwise.wproj

Bước 12: Sau khi mở, hãy mở mục Audio
 và mở Actor-Mixer Hierarchy

 Tiếp theo, mở Default Work Unit

 Bây giờ chúng ta mở voice và có rất nhiều vùng trống, chúng ta phải chèn các tệp âm thanh vào chúng, đây là danh sách chúng:

 (Các cụm từ được theo sau bởi tên của tệp âm thanh và định dạng của nó, cụm từ được lưu dưới tên và định dạng mong muốn)

 (Chỉ cần chuyển tệp âm thanh từ thư mục sang program trong vùng trống mong muốn, nó sẽ tự thiết lập (nếu có tên và định dạng chính xác))
# Tiếng Kíp Lái
# ally_killed_by_player
tiêu diệt đồng minh
* ally_killed_by_player_01.wav
* ally_killed_by_player_02.wav

# ammo_bay_damaged
gác đạn bị hư hại
* ammo_bay_damaged_01.wav
* ammo_bay_damaged_02.wav
* ammo_bay_damaged_03.wav

# armor_not_pierced_by_player
bắn hụt
* armor_not_pierced_by_player_01.wav
* armor_not_pierced_by_player_02.wav
* armor_not_pierced_by_player_03.wav
* armor_not_pierced_by_player_04.wav
* armor_not_pierced_by_player_05.wav

# armor_pierced_by_player
bắn trúng
* armor_pierced_by_player_01.wav
* armor_pierced_by_player_02.wav
* armor_pierced_by_player_03.wav
* armor_pierced_by_player_04.wav
* armor_pierced_by_player_05.wav
* armor_pierced_by_player_06.wav
* armor_pierced_by_player_07.wav
* armor_pierced_by_player_08.wav
* armor_pierced_by_player_09.wav
* armor_pierced_by_player_10.wav
* armor_pierced_by_player_11.wav
* armor_pierced_by_player_12.wav

# armor_pierced_crit_by_player
xuyên giáp
* armor_pierced_crit_by_player_01.wav
* armor_pierced_crit_by_player_02.wav
* armor_pierced_crit_by_player_03.wav
* armor_pierced_crit_by_player_04.wav
* armor_pierced_crit_by_player_05.wav
* armor_pierced_crit_by_player_06.wav
* armor_pierced_crit_by_player_07.wav
* armor_pierced_crit_by_player_08.wav
* armor_pierced_crit_by_player_09.wav

# armor_ricochet_by_player
nảy đạn
* armor_ricochet_by_player_01.wav
* armor_ricochet_by_player_02.wav
* armor_ricochet_by_player_03.wav
* armor_ricochet_by_player_04.wav
* armor_ricochet_by_player_05.wav
* armor_ricochet_by_player_06.wav
* armor_ricochet_by_player_07.wav

# commander_killed
chỉ huy bị thương 
* commander_killed_01.wav
* commander_killed_02.wav
* commander_killed_03.wav

# driver_killed
lái xe bị thương
* driver_killed_01.wav
* driver_killed_02.wav
* driver_killed_03.wav

# enemy_fire_started_by_player
bắn cháy xe
* enemy_fire_started_by_player_01.wav
* enemy_fire_started_by_player_02.wav
* enemy_fire_started_by_player_03.wav
* enemy_fire_started_by_player_04.wav

# enemy_killed_by_player
tiêu diệt địch
* enemy_killed_by_player_01.wav
* enemy_killed_by_player_02.wav
* enemy_killed_by_player_03.wav
* enemy_killed_by_player_04.wav
* enemy_killed_by_player_05.wav
* enemy_killed_by_player_06.wav
* enemy_killed_by_player_07.wav
* enemy_killed_by_player_08.wav
* enemy_killed_by_player_09.wav

# engine_damaged
hỏng nhẹ động cơ
* engine_damaged_01.wav
* engine_damaged_02.wav
* engine_damaged_03.wav
* engine_damaged_04.wav
* engine_damaged_05.wav

# engine_destroyed
hỏng hoàn toàn động cơ
* engine_destroyed_01.wav
* engine_destroyed_02.wav
* engine_destroyed_03.wav

# engine_functional
động cơ khôi phục 1 phần
* engine_functional_01.wav
* engine_functional_02.wav

# fire_started
xe bị cháy
* fire_started_01.wav
* fire_started_02.wav

# fire_stopped
đã dập cháy
* fire_stopped_01.wav
* fire_stopped_02.wav
* fire_stopped_03.wav

# fuel_tank_damaged
thùng xăng bị hư hại
* fuel_tank_damaged_01.wav
* fuel_tank_damaged_02.wav
* fuel_tank_damaged_03.wav
* fuel_tank_damaged_04.wav

# gun_damaged
súng hỏng nhẹ
* gun_damaged_01.wav
* gun_damaged_02.wav
* gun_damaged_03.wav
* gun_damaged_04.wav

# gun_destroyed
súng hỏng hoàn toàn
* gun_destroyed_01.wav
* gun_destroyed_02.wav
* gun_destroyed_03.wav

# gun_functional
đã sửa súng 1 phần
* gun_functional_01.wav
* gun_functional_02.wav
* gun_functional_03.wav
* gun_functional_04.wav

# gunner_killed
súng thủ bị thương 
* gunner_killed_01.wav
* gunner_killed_02.wav
* gunner_killed_03.wav

# loader_killed
nạp đạn bị thương
* loader_killed_01.wav
* loader_killed_02.wav

# radio_damaged
radio bị hỏng (không có trong game)
* radio_damaged_01.wav
* radio_damaged_02.wav
* radio_damaged_03.wav
* radio_damaged_04.wav
* radio_damaged_05.wav

# radioman_killed
người điều khiển radio bị thương (không có trong game)

* radioman_killed_01.wav

# start_battle
tham chiến!
* start_battle_01.wav
* start_battle_02.wav
* start_battle_03.wav
* start_battle_04.wav
* start_battle_05.wav
* start_battle_06.wav
* start_battle_07.wav
* start_battle_08.wav

# surveying_devices_damaged
ống nhòm bị hỏng nhẹ
* surveying_devices_damaged_01.wav
* surveying_devices_damaged_02.wav
* surveying_devices_damaged_03.wav
* surveying_devices_damaged_04.wav
* surveying_devices_damaged_05.wav

# surveying_devices_destroyed
ống nhòm bị hỏng hoàn toàn 
* surveying_devices_destroyed_01.wav
* surveying_devices_destroyed_02.wav
* surveying_devices_destroyed_03.wav
* surveying_devices_destroyed_04.wav
* surveying_devices_destroyed_05.wav
* surveying_devices_destroyed_06.wav

# surveying_devices_functional
đã sửa ống nhòm
* surveying_devices_functional_01.wav
* surveying_devices_functional_02.wav
* surveying_devices_functional_03.wav
* surveying_devices_functional_04.wav
* surveying_devices_functional_05.wav
* surveying_devices_functional_06.wav

# track_cut
chặt xích
* track_destroyed_cut_01.wav

# track_damaged
xích hỏng nhẹ
* track_damaged_01.wav
* track_damaged_02.wav
* track_damaged_03.wav
* track_damaged_04.wav

# track_destroyed
xích hỏng hoàn toàn
* track_destroyed_01.wav
* track_destroyed_02.wav
* track_destroyed_03.wav
* track_destroyed_04.wav

# track_functional
sửa xích
* track_functional_01.wav
* track_functional_02.wav
* track_functional_03.wav
* track_functional_04.wav

# track_functional_can_move
xích đã sửa, đi thôi!
* track_functional_can_move_01.wav
* track_functional_can_move_02.wav
* track_functional_can_move_03.wav
* track_functional_can_move_04.wav
* track_functional_can_move_05.wav

# turret_rotator_damaged
tháp pháo hỏng nhẹ
* turret_rotator_damaged_01.wav
* turret_rotator_damaged_02.wav

# turret_rotator_destroyed
tháp pháo hỏng hoàn toàn
* turret_rotator_destroyed_01.wav
* turret_rotator_destroyed_02.wav

# turret_rotator_functional
tháp pháo đã sửa 1 phần
* turret_rotator_functional_01.wav
* turret_rotator_functional_02.wav

# vehicle_destroyed
xe tăng bị phá hủy
* vehicle_destroyed_01.wav
* vehicle_destroyed_02.wav
* vehicle_destroyed_03.wav

# =========================

Sau khi làm xong, Mở mục SoundBanks và
Mở Default Work Unit, nhấp chuột phải vào voiceover_crew và nhấp Generate Soundbank(s) for current platform

Sau khi tạo xong, kết quả sẽ là 
Completed with error(s) và dòng chữ màu đỏ

Tiếp theo,Chúng ta mở thư mục dự án (để giải nén nó ra) và mở thư mục GeneratedSoundBanks trong đó sau đó Mở thư mục Windows rồi English (Us)

Bên trong thư mục này sẽ có file voiceover_crew.bnk là file kíp lái của chúng ta đã chỉnh sửa

sau đó dùng tool chuyển sang định dạng dvpl

# Hướng dẫn Cài file kíp lái
# Steam:
Steam/SteamApps/Common/World of Tanks Blitz/files/WwiseSound/(chọn ngôn ngữ tùy thích, tại đây mình sẽ chọn vi)
# Android:
Android/Data/net.wargaming.Wot.Blitz/files/WwiseSound/(chọn ngôn ngữ tùy thích, tại đây mình sẽ chọn vi)

Hi vọng Hương Dẫn này sẽ cho bạn biết cách tự mod kíp lái

Chúc các bạn thành công!

Tác giả : Huntez
https://youtube.com/HuntezChannel

Việt hóa: _____Kurumi_Nanase___

Donate cho Hutez:
https://donationalerts.com/r/Huntez

