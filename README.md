[Adblock Plus 2.0]
! title: 乘风 视频广告过滤规则
! Version: 202105021
! Expires: 2 days
! Homepage: http://bbs.kafan.cn/thread-1866845-1-1.html

v.youku.com##.control-phonewatch,#right-title-ad-banner
youku.com##+js(aeld,dblclick,ykplayer.switchFullscreen)
!v.youku.com##+js(nano-stb)
||atm.youku.com/
||cibntv.net/youku/$media
||valipl.cp31.ott.cibntv.net/$media
|https://js.ykimg.com/youku/dist/js/lib/ikuAdapterNew.js
||sealine.youku.com/yk/*callback=adpagesdk$script

iqiyi.com##div[data-adzone],#block-V
!iqiyi.com##+js(nano-sib)
iqiyi.com##+js(set, Object.prototype.parseXML, noopFunc)
!||t7z.cupid.iqiyi.com/show$script,important
||static.iqiyi.com/js/common/mars_v.js$script
||iqiyi.com/videos/other/20$xmlhttprequest,object-subrequest
||iqiyipic.com/image/20*_100000$image
||ssports.iqiyi.com/json/shop/shopInfo
show.ssports.com
||ssports.iqiyi.com/app/$object-subrequest

qq.com##.mod_ad, .txp_ad
v.qq.com,sports.qq.com##+js(json-prune,ad,vinfo)
v.qq.com,sports.qq.com##+js(nano-sib, \u5012\u8ba1\u65f6)
@@||video.qq.com/fcgi-bin/
||mark.l.qq.com/fcgi-bin/get_video_mark_all?idlist=
||gtimg.com/qqlive/
miaozhen.com
reachmax.cn
scorecardresearch.com
tencentmind.com
xtgreat.com

bilibili.com##.gg-floor-module,#slide_ad,#slide_ad+a[data-target-url]
||api.bilibili.com/x/web-show/res/loc?pf=$~script
||hdslb.com/bfs/sycp/creative_img/$image

acfun.cn##.pause-display-container,#ad-comment,#ad-player-view
||aixifan.com/static/*/appGuide/

cctv.com###bgAd_div
cctv.com,ddrk.me##+js(aeld,dblclick,isImmediatePropagationStopped)
||imall.cctv.com/$subdocument
||bjcathay.com/
!||player.cntv.cn/h5vod/$script

pptv.com##div[id^=afp_],div[id$=-afp],#video-download-game
||synacast.com
||de.as.pptv.com^
||g.pptv.com/game/$subdocument

@@||tb.mgtv.com/sdk/*/ad-sdk.js$script
||video.da.mgtv.com/$media
ys.da.mgtv.com
||da.mgtv.com/mediafiles/wiad_creative/$image

@@||js.tv.itc.cn/gg.seed.js
||css.tv.itc.cn/m/img/player/dlBanner.$image
||data.vod.itc.cn/*&prod=ad&$media
||api.my.tv.sohu.com/wm/getads.do?
||aty.sohu.com/
||go.sohu.com/
||tv.sohu.com/upload/csad/admaster/$image
tv.sohu.com##.x-dl-shake.x-download-panel, #playerBar > div.area ~a

1905.com##.ad-couplet,#hd-tab-label4,div.bd-tab.video-list:last-child
||aliyun.com^$domain=1905.com
||aliyuncs.com^$domain=1905.com

@@||ark.letv.com/adx?adzone=
@@||stat.letv.com/$script
*/letv-gug/$media,object-subrequest
||letvimg.com/$object,object-subrequest
||letvimg.com/*_gugwl/$image
||js.letvcdn.com/*_banner_$script
||banana.le.com/
adxvip.com
behe.com
biddingx.com
cr-nielsen.com
fancyapi.com
kejet.net
||jd.com/$domain=le.com
ulmdb.cn
yoyi.com.cn
zhiziyun.com
le.com##.banner_ad,div.banner_left,div.banner_right,.min_pause_img

douyu.com##div[class$="-ad"],div[class|=ad],div.no-login
||douyucdn.cn/adxdsp/$image
||wan.douyu.com/
douyu.com,huya.com##a[href^="https://g.wan."]
huya.com###hy-ad,#hy-ab,#huya-ab
||g.huya.com/

||pub.funshion.com

*/preroll/$media,domain=91porn.com
||91p20.space^
||waust.at^

dililitv.cc,lzvod.net##+js(aeld,dblclick,dp.fullScreen.request)
||www.dililitv.cc/*.php?ad=$script
js.dilidd.com
dililitv.cc,hmtv.me,imeiju.io##+js(acis,Object.defineProperty,location.href)

dyjihe.com##.tempWrap

haitur.com,haicaoys.com##.dplayer-web-fullscreen-fix .float-box
haitur.com##.container:style(max-width:90%!important;width:90%!important)
haitur.com##.left-content:style(width:77%!important)

imomoe.*,xiamov.com,xxdm8.com##+js(ra, target, base[target])
dyjihe.com,haicaoys.com,haitur.com,imomoe.*,kakadm.com,milimili.tv,qiqidongman.com,vodxc.in##+js(ra, target, a[href^="/"])
||alicdn.com/$image,domain=api.xiaomingming.org
imomoe.*###adl,#adr

yatu.tv##.dplayer-web-fullscreen-fix #tburl,#loadtop,[id^=myas],#myds1,#daohang
yatu.tv##+js(set,document.oncontextmenu,null)
||tracker.$xhr,websocket,script,ping
3z9e.cn
7nsc.cn
7b6l2j.cn
anquanzhuomian.com
ch-hr12333.com
g1c5.com
ieeod0.com
fourier.taobao.com
v4dwkcv.com
weizhenwx.com
youle55.com

bmbaike.cn
buzx53.cn
cqqc3.com
dacedsfa.cn
qdwght.com
quickapp.cn
xcsci.cn
xixiqiu.com
xv5b.com
xz6d.com
||www.yatu.tv:88/image/*.gif^$image
||www.yatu.tv:88/m/images/$image
