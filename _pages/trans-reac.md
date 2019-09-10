---
title: "Translate - Reaction Based"
permalink: /trans-reac/
excerpt: "Translate by Reacting to a Message"
last_modified_at: 2019-09-10T14:00:00+01:00   #Please Update, The +00:00 is the Time Zone difference
redirect_from:
  - /theme-setup/
toc: true

# Date formatting & Date Parsing - Let formatting and parsing date expressed in ISO8601 format.
# Can be obtained from https://dencode.com/en/date
# ---- Defined ----
# YYYY-MM-DD'T'hh:mm:ssTZD (e.g. 2015-12-11T20:28:30+01:00)
# YYYY = four-digit year
# MM = two-digit month (01=January, etc.)
# DD = two-digit day of month (01 through 31)
# hh = two digits of hour (00 through 23) (am/pm NOT allowed)
# mm = two digits of minute (00 through 59)
# ss = two digits of second (00 through 59)
# TZD = time zone designator (Z or +hh:mm or -hh:mm)
---

**Important Note**

*The bot's default prefix is !t (or !translate) - All commands must start with this prefix for the bot to process them.
Bot must have proper permissions in all relevant channels for full functionality (**read**, **write**, **react**, **mention**, **attachments**, **embed**).*

*Users who wish to receive automatic translations in private must **enable DMs** via **server privacy settings**.*

----

Translates a message in the server when you react to it with a flag emoji.

The full Supported list can be found below

| Flag | Flag Code | Country | Translates to |
|------|-----------|------------------------------------|--------------------|
| https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/twitter/214/flag-for-afghanistan_1f1e6-1f1eb.png | :flag_af: | Afghanistan | ps |
| (/assets/images/flags/named/flag_ax.jpg) | :flag_ax: | Aland Islands | sv |
| (assets/images/flags/named/flag_al.jpg) | :flag_al: | Albania | sq |
| [](assets/images/flags/named/flag_dz.jpg) | :flag_dz: | Algeria | ar, fr |
| ![](assets/images/flags/named/flag_as.jpg) | :flag_as: | American Samoa | en, sm |
| [](/assets/images/flags/named/flag_ad.jpg) | :flag_ad: | Andorra | ca |
| ![](/assets/images/flags/named/flag_ad.jpg) | :flag_ao: | Angola | pt |
| <img src="/assets/images/flags/named/flag_ai.jpg" alt="flag_ai"/>  | :flag_ai: | Anguilla | en |
|  | :flag_aq: | Antarctica | null |
|  | :flag_ag: | Antigua And Barbuda | en |
|  | :flag_ar: | Argentina | es |
|  | :flag_am: | Armenia | hy |
|  | :flag_aw: | Aruba | nl |
|  | :flag_au: | Australia | en |
|  | :flag_at: | Austria | de |
|  | :flag_az: | Azerbaijan | az |
|  | :flag_bs: | Bahamas | en |
|  | :flag_bh: | Bahrain | ar |
|  | :flag_bd: | Bangladesh | bn |
|  | :flag_bb: | Barbados | en |
|  | :flag_by: | Belarus | be, ru |
|  | :flag_be: | Belgium | nl, fr, de |
|  | :flag_bz: | Belize | en, es |
|  | :flag_bj: | Benin | fr |
|  | :flag_bm: | Bermuda | en |
|  | :flag_bt: | Bhutan | dz |
|  | :flag_bo: | Bolivia | es |
|  | :flag_ba: | Bosnia And Herzegovina | bs, hr, sr |
|  | :flag_bw: | Botswana | en |
|  | :flag_bv: | Bouvet Island | no |
|  | :flag_br: | Brazil | pt |
|  | :flag_io: | British Indian Ocean Territory | en |
|  | :flag_bn: | Brunei Darussalam | ms, en |
|  | :flag_bg: | Bulgaria | bg |
|  | :flag_bf: | Burkina Faso | fr |
|  | :flag_bi: | Burundi | fr, rn |
|  | :flag_kh: | Cambodia | km |
|  | :flag_cm: | Cameroon | fr, en |
|  | :flag_ca: | Canada | en, fr |
|  | :flag_cv: | Cape Verde | pt |
|  | :flag_ky: | Cayman Islands | en |
|  | :flag_cf: | Central African Republic | fr, sg |
|  | :flag_td: | Chad | ar, fr |
|  | :flag_cl: | Chile | es |
|  | :flag_cn: | China | zh-cn |
|  | :flag_cx: | Christmas Island | zh-cn, en, ms |
|  | :flag_cc: | Cocos (Keeling) Islands | ms, en |
|  | :flag_co: | Colombia | es |
|  | :flag_km: | Comoros | ar, fr |
|  | :flag_cg: | Republic of the Congo | fr, ln |
|  | :flag_cd: | Democratic Republic of the Congo | fr, sw |
|  | :flag_ck: | Cook Islands | en |
|  | :flag_cr: | Costa Rica | es |
|  | :flag_ci: | Cote D'Ivoire | fr |
|  | :flag_hr: | Croatia | hr |
|  | :flag_cu: | Cuba | es |
|  | :flag_cy: | Cyprus | el, tr |
|  | :flag_cz: | Czech Republic | cs |
|  | :flag_dk: | Denmark | da |
|  | :flag_dj: | Djibouti | ar, fr |
|  | :flag_dm: | Dominica | en |
|  | :flag_do: | Dominican Republic | es |
|  | :flag_ec: | Ecuador | es |
|  | :flag_eg: | Egypt | ar |
|  | :flag_sv: | El Salvador | es |
|  | :flag_gq: | Equatorial Guinea | es, fr, pt |
|  | :flag_er: | Eritrea | ar, en, ti |
|  | :flag_ee: | Estonia | et |
|  | :flag_et: | Ethiopia | or, am, so, ti |
|  | :flag_fk: | Falkland Islands (Malvinas) | en |
|  | :flag_fo: | Faroe Islands | da, fo |
|  | :flag_fj: | Fiji | fj, en |
|  | :flag_fi: | Finland | fi, sv |
|  | :flag_fr: | France | fr |
|  | :flag_gf: | French Guiana | fr |
|  | :flag_pf: | French Polynesia | fr |
|  | :flag_tf: | French Southern Territories | fr |
|  | :flag_ga: | Gabon | fr |
|  | :flag_gm: | Gambia | en |
|  | :flag_ge: | Georgia | ka |
|  | :flag_de: | Germany | de |
|  | :flag_gh: | Ghana | en |
|  | :flag_gi: | Gibraltar | en, es |
|  | :flag_gr: | Greece | el |
|  | :flag_gl: | Greenland | kl, da |
|  | :flag_gd: | Grenada | en |
|  | :flag_gp: | Guadeloupe | fr |
|  | :flag_gu: | Guam | en, ch |
|  | :flag_gt: | Guatemala | es |
|  | :flag_gg: | Guernsey | en |
|  | :flag_gn: | Guinea | fr |
|  | :flag_gw: | Guinea-Bissau | pt |
|  | :flag_gy: | Guyana | en |
|  | :flag_ht: | Haiti | fr |
|  | :flag_hm: | Heard Island & Mcdonald Islands | null |
|  | :flag_va: | Holy See (Vatican City State) | la, it |
|  | :flag_hn: | Honduras | es |
|  | :flag_hk: | Hong Kong | zh-tw, en |
|  | :flag_hu: | Hungary | hu |
|  | :flag_is: | Iceland | is |
|  | :flag_in: | India | hi |
|  | :flag_id: | Indonesia | id |
|  | :flag_ir: | Iran | fa |
|  | :flag_iq: | Iraq | ar, ku |
|  | :flag_ie: | Ireland | en, ga |
|  | :flag_im: | Isle Of Man | en, gv |
|  | :flag_il: | Israel | he, ar |
|  | :flag_it: | Italy | it |
|  | :flag_jm: | Jamaica | en |
|  | :flag_jp: | Japan | ja |
|  | :flag_je: | Jersey | en |
|  | :flag_jo: | Jordan | ar |
|  | :flag_kz: | Kazakhstan | kk, ru |
|  | :flag_ke: | Kenya | en, sw |
|  | :flag_ki: | Kiribati | en |
|  | :flag_kr: | South Korea | ko |
|  | :flag_kw: | Kuwait | ar |
|  | :flag_kg: | Kyrgyzstan | ky, ru |
|  | :flag_la: | Lao People's Democratic Republic | lo |
|  | :flag_lv: | Latvia | lv |
|  | :flag_lb: | Lebanon | ar |
|  | :flag_ls: | Lesotho | st, en |
|  | :flag_lr: | Liberia | en |
|  | :flag_ly: | Libya | ar |
|  | :flag_li: | Liechtenstein | de |
|  | :flag_lt: | Lithuania | lt |
|  | :flag_lu: | Luxembourg | lb, fr, de |
|  | :flag_mo: | Macao | zh-tw, pt |
|  | :flag_mk: | Macedonia | mk |
|  | :flag_mg: | Madagascar | mg, fr |
|  | :flag_mw: | Malawi | en |
|  | :flag_my: | Malaysia | ms |
|  | :flag_mv: | Maldives | dv |
|  | :flag_ml: | Mali | fr |
|  | :flag_mt: | Malta | mt |
|  | :flag_mh: | Marshall Islands | mh, en |
|  | :flag_mq: | Martinique | fr |
|  | :flag_mr: | Mauritania | ar |
|  | :flag_mu: | Mauritius | en, fr |
|  | :flag_yt: | Mayotte | fr |
|  | :flag_mx: | Mexico | es |
|  | :flag_fm: | Micronesia | en |
|  | :flag_md: | Moldova | ro |
|  | :flag_mc: | Monaco | fr |
|  | :flag_mn: | Mongolia | mn |
|  | :flag_me: | Montenegro | cnr |
|  | :flag_ms: | Montserrat | en |
|  | :flag_ma: | Morocco | ar |
|  | :flag_mz: | Mozambique | pt |
|  | :flag_mm: | Myanmar | my |
|  | :flag_na: | Namibia | en |
|  | :flag_nr: | Nauru | na |
|  | :flag_np: | Nepal | ne |
|  | :flag_nl: | Netherlands | nl |
|  | :flag_an: | Netherlands Antilles | nl |
|  | :flag_nc: | New Caledonia | fr |
|  | :flag_nz: | New Zealand | en |
|  | :flag_ni: | Nicaragua | es |
|  | :flag_ne: | Niger | fr |
|  | :flag_ng: | Nigeria | en |
|  | :flag_nu: | Niue | en, niu |
|  | :flag_nf: | Norfolk Island | en |
|  | :flag_mp: | Northern Mariana Islands | en, ch, cal |
|  | :flag_no: | Norway | no |
|  | :flag_om: | Oman | ar |
|  | :flag_pk: | Pakistan | ur |
|  | :flag_pw: | Palau | en, pau |
|  | :flag_ps: | Palestinian Territory | ar |
|  | :flag_pa: | Panama | es |
|  | :flag_pg: | Papua New Guinea | en, ho, tpi |
|  | :flag_py: | Paraguay | es, gug |
|  | :flag_pe: | Peru | es |
|  | :flag_ph: | Philippines | tl |
|  | :flag_pn: | Pitcairn | en |
|  | :flag_pl: | Poland | pl |
|  | :flag_pt: | Portugal | pt |
|  | :flag_pr: | Puerto Rico | es |
|  | :flag_qa: | Qatar | ar |
|  | :flag_re: | Reunion | fr |
|  | :flag_ro: | Romania | ro |
|  | :flag_ru: | Russian Federation | ru |
|  | :flag_rw: | Rwanda | rw, en, fr, sw |
|  | :flag_bl: | Saint Barthelemy | fr |
|  | :flag_sh: | Saint Helena | en |
|  | :flag_kn: | Saint Kitts And Nevis | en |
|  | :flag_lc: | Saint Lucia | en |
|  | :flag_mf: | Saint Martin | nl, fr |
|  | :flag_pm: | Saint Pierre And Miquelon | fr |
|  | :flag_vc: | Saint Vincent And Grenadines | en |
|  | :flag_ws: | Samoa | sm, en |
|  | :flag_sm: | San Marino | it |
|  | :flag_st: | Sao Tome and Principe | pt |
|  | :flag_sa: | Saudi Arabia | ar |
|  | :flag_sn: | Senegal | fr |
|  | :flag_rs: | Serbia | sr |
|  | :flag_sc: | Seychelles | en, fr |
|  | :flag_sl: | Sierra Leone | en |
|  | :flag_sg: | Singapore | en, ta, zh-tw, ms |
|  | :flag_sk: | Slovakia | sk |
|  | :flag_si: | Slovenia | sl |
|  | :flag_sb: | Solomon Islands | en |
|  | :flag_so: | Somalia | so, ar |
|  | :flag_za: | South Africa | en, af, st, xh, zu |
|  | :flag_gs: | South Georgia And Sandwich Islands | en |
|  | :flag_es: | Spain | es |
|  | :flag_lk: | Sri Lanka | si, ta |
|  | :flag_sd: | Sudan | ar |
|  | :flag_sr: | Suriname | nl |
|  | :flag_sj: | Svalbard And Jan Mayen | no |
|  | :flag_sz: | Swaziland | ss, en |
|  | :flag_se: | Sweden | sv |
|  | :flag_ch: | Switzerland | de, fr, it, rm |
|  | :flag_sy: | Syrian Arab Republic | ar |
|  | :flag_tw: | Taiwan | zh-tw |
|  | :flag_tj: | Tajikistan | tg |
|  | :flag_tz: | Tanzania | sw |
|  | :flag_th: | Thailand | th |
|  | :flag_tl: | Timor-Leste | tet, pt |
|  | :flag_tg: | Togo | fr |
|  | :flag_tk: | Tokelau | tkl, en |
|  | :flag_to: | Tonga | to, en |
|  | :flag_tt: | Trinidad and Tobago | en |
|  | :flag_tn: | Tunisia | ar |
|  | :flag_tr: | Turkey | tr |
|  | :flag_tm: | Turkmenistan | tk |
|  | :flag_tc: | Turks and Caicos Islands | en |
|  | :flag_tv: | Tuvalu | tvl, en |
|  | :flag_ug: | Uganda | en, sw |
|  | :flag_ua: | Ukraine | uk |
|  | :flag_ae: | United Arab Emirates | ar |
| image_path: /assets/images/flags/named/flag_gb.jpg | :flag_gb: | United Kingdom | en |
|  | :flag_us: | United States | en |
|  | :flag_um: | United States Outlying Islands | en |
|  | :flag_uy: | Uruguay | es, pt |
|  | :flag_uz: | Uzbekistan | uz |
|  | :flag_vu: | Vanuatu | bi, en, fr |
|  | :flag_ve: | Venezuela | es |
|  | :flag_vn: | Vietnam | vi |
|  | :flag_vg: | British Virgin Islands | en |
|  | :flag_vi: | Us Virgin Islands | en |
|  | :flag_wf: | Wallis and Futuna | fr |
|  | :flag_eh: | Western Sahara | ar |
|  | :flag_ye: | Yemen | ar |
|  | :flag_zm: | Zambia | en |
|  | :flag_zw: | Zimbabwe | ny, en, xh, st, sn |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
