海康威视Android studio版 具体参数可以在界面上设置

HCNetSDK.getInstance().NET_DVR_Init() //初始化

HCNetSDK.getInstance().NET_DVR_Logout_V30(m_iLogID) //退出登录

HCNetSDK.getInstance().NET_DVR_Login_V30(strIP, nPort,strUser, strPsd, m_oNetDvrDeviceInfoV30) //登录NVR

HCNetSDK.getInstance().NET_DVR_RealPlay_V40(m_iLogID,previewInfo, fRealDataCallBack)//视频流回调

HCNetSDK.getInstance().NET_DVR_StopSaveRealData(m_iPlayID)//停止播放