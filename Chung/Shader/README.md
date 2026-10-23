# Shader theo nền tảng + Áo Đấu Blue Look

Chung/Shader/<BẢN>/shaders.*   : bundle shader dùng chung (CAB-1dc8) của từng bản game.
  ADR_FFMAX  -> GLES3  (nhân vật ADR FF MAX)
  IOS_FFTH   -> Metal  (nhân vật iOS FF THƯỜNG)
  IOS_FFMAX  -> Metal  (nhân vật iOS FF MAX)
  (ADR FF THƯỜNG dùng file Chung/shaders.OMFd4hA1zxkPVCeTGXNDssFQbgI~3D đã có sẵn.)
  Tên thư mục chứa "MAX" / "FFTH" giúp tool chọn đúng bản TH hay MAX cho iOS.

Top/Áo Đấu Blue Look/optionalab_551... : asset ADR FF THƯỜNG của Áo Đấu Blue Lock
  (UMAMaterial + Material: DTSAvatarCutOff_Cartoon, DTSAvatarCommonCutOff, ...).

Món đồ mới chỉ cần asset ADR FF THƯỜNG. Bot tự chép MonoBehaviour UMAMaterial + Material,
còn Shader thì lấy đúng bản của nhân vật (ADR TH / ADR MAX / iOS) và đổi sang định dạng của nhân vật.
