# whelcome to room fukeboy
#!/usr/bin/env python3
#-*- pengkodean: utf-8 -*-
#github.com/AngelSecurityTeam/Cam-Hackers

permintaan impor, re , colorama
colorama.init()
mencetak("""
\033[1;31m\033[1;37m █╗██╗ ██╗███████╗██████╗ ███████╗.
██╔════╝██╔══██╗████╗ ████║ ██║ ██║██╔══██╗██╔═══╝██ ║ ██╔╝██╔═══╝██╔══██╗██╔═══╝.
██║ ███████║██╔████╔██║██████║███████████║ ███. ██╔╝ █████╗ ███████╗███████╗.
██║ ██╔══██║██║╚██╔╝██║╚═══╝██╔══██║██╔══██║║║ ██╔. ═██╗ ██╔══╝ ██╔══██╗╚═══██║.
╚██████╗██║ ██║██║ ╚═╝ ██║ ██║ ██║██║ ██║╚██████╗██║ ██╗█ ██████╗██║ ██║███████║.
\033[1;31m ╚═╝ ╚══════╝╚═╝ ╚═╝╚═════╝.
\033[1;31m ANGELSECURITYTEAM
\033[1;31m1) \033[1;37mAmerika Serikat \033[1;31m31) \033[1;37mMexico \033[1;31m61) \033[1;37mMoldova
\033[1;31m2) \033[1;37mJapan \033[1;31m32) \033[1;37mFinland \033[1;31m62) \033[1;37mNikaragua
\033[1;31m3) \033[1;37mItalia \033[1;31m33) \033[1;37mChina \033[1;31m63) \033[1;37mMalta
\033[1;31m4) \033[1;37mKorea \033[1;31m34) \033[1;37mChile \033[1;31m64) \033[1;37mTrinidad And Tobago
\033[1;31m5) \033[1;37mFrance \033[1;31m35) \033[1;37mAfrika Selatan \033[1;31m65) \033[1;37mArab Saudi
\033[1;31m6) \033[1;37mJerman \033[1;31m36) \033[1;37mSlovakia \033[1;31m66) \033[1;37mKroasia
\033[1;31m7) \033[1;37mTaiwan \033[1;31m37) \033[1;37mHungary \033[1;31m67) \033[1;37mCyprus
\033[1;31m8) \033[1;37mFederasi Rusia \033[1;31m38) \033[1;37mIreland \033[1;31m68) \033[1;37mPakistan
\033[1;31m9) \033[1;37mUnited Kingdom \033[1;31m39) \033[1;37mEgypt \033[1;31m69) \033[1;37mUni Emirat Arab
\033[1;31m10) \033[1;37mBelanda \033[1;31m40) \033[1;37mThailand \033[1;31m70) \033[1;37mKazakhstan
\033[1;31m11) \033[1;37mRepublik Ceko \033[1;31m41) \033[1;37mUkraine \033[1;31m71) \033[1;37mKuwait
\033[1;31m12) \033[1;37mTurki \033[1;31m42) \033[1;37mSerbia \033[1;31m72) \033[1;37mVenezuela
\033[1;31m13) \033[1;37mAustria \033[1;31m43) \033[1;37mHong Kong \033[1;31m73) \033[1;37mGeorgia
\033[1;31m14) \033[1;37mSwiss \033[1;31m44) \033[1;37mYunani \033[1;31m74) \033[1;37mMontenegro
\033[1;31m15) \033[1;37mSpany \033[1;31m45) \033[1;37mPortugal \033[1;31m75) \033[1;37mEl Salvador
\033[1;31m16) \033[1;37mCanada \033[1;31m46) \033[1;37mLatvia \033[1;31m76) \033[1;37mLuxembourg
\033[1;31m17) \033[1;37mSweden \033[1;31m47) \033[1;37mSingapore \033[1;31m77) \033[1;37mCuracao
\033[1;31m18) \033[1;37mIsrael \033[1;31m48) \033[1;37mIceland \033[1;31m78) \033[1;37mPuerto Rico
\033[1;31m19) \033[1;37mIran \033[1;31m49) \033[1;37mMalaysia \033[1;31m79) \033[1;37mKosta Rika
\033[1;31m20) \033[1;37mPolandia \033[1;31m50) \033[1;37mColombia \033[1;31m80) \033[1;37mBelarus
\033[1;31m21) \033[1;37mIndia \033[1;31m51) \033[1;37mTunisia \033[1;31m81) \033[1;37mAlbania
\033[1;31m22) \033[1;37mNorway \033[1;31m52) \033[1;37mEstonia \033[1;31m82) \033[1;37mLiechtenstein
\033[1;31m23) \033[1;37mRumania \033[1;31m53) \033[1;37mRepublik Dominika \033[1;31m83) \033[1;37mBosnia dan Herzegovia
\033[1;31m24) \033[1;37mViet Nam \033[1;31m54) \033[1;37mSloveania \033[1;31m84) \033[1;37mParaguay
\033[1;31m25) \033[1;37mBelgium \033[1;31m55) \033[1;37mEcuador \033[1;31m85) \033[1;37mFilipina
\033[1;31m26) \033[1;37mBrazil \033[1;31m56) \033[1;37mLithuania \033[1;31m86) \033[1;37mKepulauan Faroe
\033[1;31m27) \033[1;37mBulgaria \033[1;31m57) \033[1;37mPalestina \033[1;31m87) \033[1;37mGuatemala
\033[1;31m28) \033[1;37mIndonesia \033[1;31m58) \033[1;37mSelandia Baru \033[1;31m88) \033[1;37mNepal
\033[1;31m29) \033[1;37mDenmark \033[1;31m59) \033[1;37mBangladeh \033[1;31m89) \033[1;37mPeru
\033[1;31m30) \033[1;37mArgentina \033[1;31m60) \033[1;37mPanama \033[1;31m90) \033[1;37mUruguay
                                                          \033[1;31m91) \033[1;37mEkstra
""")

mencoba:
    mencetak()
    negara = ["AS", "JP", "IT", "KR", "FR", "DE", "TW", "RU", "GB", "NL",
                 "CZ", "TR", "AT", "CH", "ES", "CA", "SE", "IL", "PL", "IR",
                 "TIDAK", "RO", "IN", "VN", "BE", "BR", "BG", "ID", "DK", "AR",
                 "MX", "FI", "CN", "CL", "ZA", "SK", "HU", "IE", "EG", "TH",
                 "UA", "RS", "HK", "GR", "PT", "LV", "SG", "ADALAH", "MY", "CO",
                 "TN", "EE", "DO", "SI", "EC", "LT", "PS", "NZ", "BD", "PA",
                 "MD", "NI", "MT", "IT", "SA", "HR", "CY", "PK", "AE", "KZ",
                 "KW", "VE", "GE", "ME", "SV", "LU", "CW", "PR", "CR", "BY",
                 "AL", "LI", "BA", "PY", "PH", "FO", "GT", "NP", "PE", "UY",
                 "-"]
    headers = {"User-Agent": "Mozilla/5.0 (X11; Linux i686; rv:68.0) Gecko/20100101 Firefox/68.0"}

    bilangan = int(input("PILIHAN : "))
    jika num tidak dalam kisaran (1, 91+1):
        meningkatkan IndexError

    negara = negara[angka-1]
    res = permintaan. dapatkan(
        f"https://www.insecam.org/en/bycountry/{country}", headers=headers
    )
    last_page = re.findall(r'pagenavigator\("\?page=", (\d+)', res.text)[0]

    untuk halaman dalam rentang(int(last_page)):
        res = permintaan. dapatkan(
            f"https://www.insecam.org/en/bycountry/{country}/?page={page}",
            tajuk = tajuk
        )
        find_ip = re.findall(r"http://\d+.\d+.\d+.\d+:\d+", res.text)
        untuk ip di find_ip:
            print("\033[1;31m", ip)
kecuali:
    lulus
akhirnya:
    print("\033[1;37m")
    keluar()
