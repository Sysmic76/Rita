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
|-----------------------------------------------------------------------------|-----------|------------------------------------|--------------------|
| <img src="/assets/images/flags/named/flag_af.png" width="50" height="50" /> | :flag_af: | Afghanistan | ps |
| <img src="/assets/images/flags/named/flag_ax.png" width="50" height="50" /> | :flag_ax: | Aland Islands | sv |
| <img src="/assets/images/flags/named/flag_al.png" width="50" height="50" /> | :flag_al: | Albania | sq |
| <img src="/assets/images/flags/named/flag_dz.png" width="50" height="50" /> | :flag_dz: | Algeria | ar, fr |
| <img src="/assets/images/flags/named/flag_as.png" width="50" height="50" /> | :flag_as: | American Samoa | en, sm |
| <img src="/assets/images/flags/named/flag_ad.png" width="50" height="50" /> | :flag_ad: | Andorra | ca |
| <img src="/assets/images/flags/named/flag_ao.png" width="50" height="50" /> | :flag_ao: | Angola | pt |
| <img src="/assets/images/flags/named/flag_ai.png" width="50" height="50" /> | :flag_ai: | Anguilla | en |
| <img src="/assets/images/flags/named/flag_aq.png" width="50" height="50" /> | :flag_aq: | Antarctica | null |
| <img src="/assets/images/flags/named/flag_ag.png" width="50" height="50" /> | :flag_ag: | Antigua And Barbuda | en |
| <img src="/assets/images/flags/named/flag_ar.png" width="50" height="50" /> | :flag_ar: | Argentina | es |
| <img src="/assets/images/flags/named/flag_am.png" width="50" height="50" /> | :flag_am: | Armenia | hy |
| <img src="/assets/images/flags/named/flag_aw.png" width="50" height="50" /> | :flag_aw: | Aruba | nl |
| <img src="/assets/images/flags/named/flag_au.png" width="50" height="50" /> | :flag_au: | Australia | en |
| <img src="/assets/images/flags/named/flag_at.png" width="50" height="50" /> | :flag_at: | Austria | de |
| <img src="/assets/images/flags/named/flag_az.png" width="50" height="50" /> | :flag_az: | Azerbaijan | az |
| <img src="/assets/images/flags/named/flag_bs.png" width="50" height="50" /> | :flag_bs: | Bahamas | en |
| <img src="/assets/images/flags/named/flag_bh.png" width="50" height="50" /> | :flag_bh: | Bahrain | ar |
| <img src="/assets/images/flags/named/flag_bd.png" width="50" height="50" /> | :flag_bd: | Bangladesh | bn |
| <img src="/assets/images/flags/named/flag_bb.png" width="50" height="50" /> | :flag_bb: | Barbados | en |
| <img src="/assets/images/flags/named/flag_by.png" width="50" height="50" /> | :flag_by: | Belarus | be, ru |
| <img src="/assets/images/flags/named/flag_be.png" width="50" height="50" /> | :flag_be: | Belgium | nl, fr, de |
| <img src="/assets/images/flags/named/flag_bz.png" width="50" height="50" /> | :flag_bz: | Belize | en, es |
| <img src="/assets/images/flags/named/flag_bj.png" width="50" height="50" /> | :flag_bj: | Benin | fr |
| <img src="/assets/images/flags/named/flag_bm.png" width="50" height="50" /> | :flag_bm: | Bermuda | en |
| <img src="/assets/images/flags/named/flag_bt.png" width="50" height="50" /> | :flag_bt: | Bhutan | dz |
| <img src="/assets/images/flags/named/flag_bo.png" width="50" height="50" /> | :flag_bo: | Bolivia | es |
| <img src="/assets/images/flags/named/flag_ba.png" width="50" height="50" /> | :flag_ba: | Bosnia And Herzegovina | bs, hr, sr |
| <img src="/assets/images/flags/named/flag_bw.png" width="50" height="50" /> | :flag_bw: | Botswana | en |
| <img src="/assets/images/flags/named/flag_bv.png" width="50" height="50" /> | :flag_bv: | Bouvet Island | no |
| <img src="/assets/images/flags/named/flag_br.png" width="50" height="50" /> | :flag_br: | Brazil | pt |
| <img src="/assets/images/flags/named/flag_io.png" width="50" height="50" /> | :flag_io: | British Indian Ocean Territory | en |
| <img src="/assets/images/flags/named/flag_bn.png" width="50" height="50" /> | :flag_bn: | Brunei Darussalam | ms, en |
| <img src="/assets/images/flags/named/flag_bg.png" width="50" height="50" /> | :flag_bg: | Bulgaria | bg |
| <img src="/assets/images/flags/named/flag_bf.png" width="50" height="50" /> | :flag_bf: | Burkina Faso | fr |
| <img src="/assets/images/flags/named/flag_bi.png" width="50" height="50" /> | :flag_bi: | Burundi | fr, rn |
| <img src="/assets/images/flags/named/flag_kh.png" width="50" height="50" /> | :flag_kh: | Cambodia | km |
| <img src="/assets/images/flags/named/flag_cm.png" width="50" height="50" /> | :flag_cm: | Cameroon | fr, en |
| <img src="/assets/images/flags/named/flag_ca.png" width="50" height="50" /> | :flag_ca: | Canada | en, fr |
| <img src="/assets/images/flags/named/flag_cv.png" width="50" height="50" /> | :flag_cv: | Cape Verde | pt |
| <img src="/assets/images/flags/named/flag_ky.png" width="50" height="50" /> | :flag_ky: | Cayman Islands | en |
| <img src="/assets/images/flags/named/flag_cf.png" width="50" height="50" /> | :flag_cf: | Central African Republic | fr, sg |
| <img src="/assets/images/flags/named/flag_td.png" width="50" height="50" /> | :flag_td: | Chad | ar, fr |
| <img src="/assets/images/flags/named/flag_cl.png" width="50" height="50" /> | :flag_cl: | Chile | es |
| <img src="/assets/images/flags/named/flag_cn.png" width="50" height="50" /> | :flag_cn: | China | zh-cn |
| <img src="/assets/images/flags/named/flag_cx.png" width="50" height="50" /> | :flag_cx: | Christmas Island | zh-cn, en, ms |
| <img src="/assets/images/flags/named/flag_cc.png" width="50" height="50" /> | :flag_cc: | Cocos (Keeling) Islands | ms, en |
| <img src="/assets/images/flags/named/flag_co.png" width="50" height="50" /> | :flag_co: | Colombia | es |
| <img src="/assets/images/flags/named/flag_km.png" width="50" height="50" /> | :flag_km: | Comoros | ar, fr |
| <img src="/assets/images/flags/named/flag_cg.png" width="50" height="50" /> | :flag_cg: | Republic of the Congo | fr, ln |
| <img src="/assets/images/flags/named/flag_cd.png" width="50" height="50" /> | :flag_cd: | Democratic Republic of the Congo | fr, sw |
| <img src="/assets/images/flags/named/flag_ck.png" width="50" height="50" /> | :flag_ck: | Cook Islands | en |
| <img src="/assets/images/flags/named/flag_cr.png" width="50" height="50" /> | :flag_cr: | Costa Rica | es |
| <img src="/assets/images/flags/named/flag_ci.png" width="50" height="50" /> | :flag_ci: | Cote D'Ivoire | fr |
| <img src="/assets/images/flags/named/flag_hr.png" width="50" height="50" /> | :flag_hr: | Croatia | hr |
| <img src="/assets/images/flags/named/flag_cu.png" width="50" height="50" /> | :flag_cu: | Cuba | es |
| <img src="/assets/images/flags/named/flag_cy.png" width="50" height="50" /> | :flag_cy: | Cyprus | el, tr |
| <img src="/assets/images/flags/named/flag_cz.png" width="50" height="50" /> | :flag_cz: | Czech Republic | cs |
| <img src="/assets/images/flags/named/flag_dk.png" width="50" height="50" /> | :flag_dk: | Denmark | da |
| <img src="/assets/images/flags/named/flag_dj.png" width="50" height="50" /> | :flag_dj: | Djibouti | ar, fr |
| <img src="/assets/images/flags/named/flag_dm.png" width="50" height="50" /> | :flag_dm: | Dominica | en |
| <img src="/assets/images/flags/named/flag_do.png" width="50" height="50" /> | :flag_do: | Dominican Republic | es |
| <img src="/assets/images/flags/named/flag_ec.png" width="50" height="50" /> | :flag_ec: | Ecuador | es |
| <img src="/assets/images/flags/named/flag_eg.png" width="50" height="50" /> | :flag_eg: | Egypt | ar |
| <img src="/assets/images/flags/named/flag_sv.png" width="50" height="50" /> | :flag_sv: | El Salvador | es |
| <img src="/assets/images/flags/named/flag_gq.png" width="50" height="50" /> | :flag_gq: | Equatorial Guinea | es, fr, pt |
| <img src="/assets/images/flags/named/flag_er.png" width="50" height="50" /> | :flag_er: | Eritrea | ar, en, ti |
| <img src="/assets/images/flags/named/flag_ee.png" width="50" height="50" /> | :flag_ee: | Estonia | et |
| <img src="/assets/images/flags/named/flag_et.png" width="50" height="50" /> | :flag_et: | Ethiopia | or, am, so, ti |
| <img src="/assets/images/flags/named/flag_fk.png" width="50" height="50" /> | :flag_fk: | Falkland Islands (Malvinas) | en |
| <img src="/assets/images/flags/named/flag_fo.png" width="50" height="50" /> | :flag_fo: | Faroe Islands | da, fo |
| <img src="/assets/images/flags/named/flag_fj.png" width="50" height="50" /> | :flag_fj: | Fiji | fj, en |
| <img src="/assets/images/flags/named/flag_fi.png" width="50" height="50" /> | :flag_fi: | Finland | fi, sv |
| <img src="/assets/images/flags/named/flag_fr.png" width="50" height="50" /> | :flag_fr: | France | fr |
| <img src="/assets/images/flags/named/flag_gf.png" width="50" height="50" /> | :flag_gf: | French Guiana | fr |
| <img src="/assets/images/flags/named/flag_pf.png" width="50" height="50" /> | :flag_pf: | French Polynesia | fr |
| <img src="/assets/images/flags/named/flag_tf.png" width="50" height="50" /> | :flag_tf: | French Southern Territories | fr |
| <img src="/assets/images/flags/named/flag_ga.png" width="50" height="50" /> | :flag_ga: | Gabon | fr |
| <img src="/assets/images/flags/named/flag_gm.png" width="50" height="50" /> | :flag_gm: | Gambia | en |
| <img src="/assets/images/flags/named/flag_ge.png" width="50" height="50" /> | :flag_ge: | Georgia | ka |
| <img src="/assets/images/flags/named/flag_de.png" width="50" height="50" /> | :flag_de: | Germany | de |
| <img src="/assets/images/flags/named/flag_gh.png" width="50" height="50" /> | :flag_gh: | Ghana | en |
| <img src="/assets/images/flags/named/flag_gi.png" width="50" height="50" /> | :flag_gi: | Gibraltar | en, es |
| <img src="/assets/images/flags/named/flag_gr.png" width="50" height="50" /> | :flag_gr: | Greece | el |
| <img src="/assets/images/flags/named/flag_gl.png" width="50" height="50" /> | :flag_gl: | Greenland | kl, da |
| <img src="/assets/images/flags/named/flag_gd.png" width="50" height="50" /> | :flag_gd: | Grenada | en |
| <img src="/assets/images/flags/named/flag_gp.png" width="50" height="50" /> | :flag_gp: | Guadeloupe | fr |
| <img src="/assets/images/flags/named/flag_gu.png" width="50" height="50" /> | :flag_gu: | Guam | en, ch |
| <img src="/assets/images/flags/named/flag_gt.png" width="50" height="50" /> | :flag_gt: | Guatemala | es |
| <img src="/assets/images/flags/named/flag_gg.png" width="50" height="50" /> | :flag_gg: | Guernsey | en |
| <img src="/assets/images/flags/named/flag_gn.png" width="50" height="50" /> | :flag_gn: | Guinea | fr |
| <img src="/assets/images/flags/named/flag_gw.png" width="50" height="50" /> | :flag_gw: | Guinea-Bissau | pt |
| <img src="/assets/images/flags/named/flag_gy.png" width="50" height="50" /> | :flag_gy: | Guyana | en |
| <img src="/assets/images/flags/named/flag_ht.png" width="50" height="50" /> | :flag_ht: | Haiti | fr |
| <img src="/assets/images/flags/named/flag_hm.png" width="50" height="50" /> | :flag_hm: | Heard Island & Mcdonald Islands | null |
| <img src="/assets/images/flags/named/flag_va.png" width="50" height="50" /> | :flag_va: | Holy See (Vatican City State) | la, it |
| <img src="/assets/images/flags/named/flag_hn.png" width="50" height="50" /> | :flag_hn: | Honduras | es |
| <img src="/assets/images/flags/named/flag_hk.png" width="50" height="50" /> | :flag_hk: | Hong Kong | zh-tw, en |
| <img src="/assets/images/flags/named/flag_hu.png" width="50" height="50" /> | :flag_hu: | Hungary | hu |
| <img src="/assets/images/flags/named/flag_is.png" width="50" height="50" /> | :flag_is: | Iceland | is |
| <img src="/assets/images/flags/named/flag_in.png" width="50" height="50" /> | :flag_in: | India | hi |
| <img src="/assets/images/flags/named/flag_id.png" width="50" height="50" /> | :flag_id: | Indonesia | id |
| <img src="/assets/images/flags/named/flag_ir.png" width="50" height="50" /> | :flag_ir: | Iran | fa |
| <img src="/assets/images/flags/named/flag_iq.png" width="50" height="50" /> | :flag_iq: | Iraq | ar, ku |
| <img src="/assets/images/flags/named/flag_ie.png" width="50" height="50" /> | :flag_ie: | Ireland | en, ga |
| <img src="/assets/images/flags/named/flag_im.png" width="50" height="50" /> | :flag_im: | Isle Of Man | en, gv |
| <img src="/assets/images/flags/named/flag_il.png" width="50" height="50" /> | :flag_il: | Israel | he, ar |
| <img src="/assets/images/flags/named/flag_it.png" width="50" height="50" /> | :flag_it: | Italy | it |
| <img src="/assets/images/flags/named/flag_jm.png" width="50" height="50" /> | :flag_jm: | Jamaica | en |
| <img src="/assets/images/flags/named/flag_jp.png" width="50" height="50" /> | :flag_jp: | Japan | ja |
| <img src="/assets/images/flags/named/flag_je.png" width="50" height="50" /> | :flag_je: | Jersey | en |
| <img src="/assets/images/flags/named/flag_jo.png" width="50" height="50" /> | :flag_jo: | Jordan | ar |
| <img src="/assets/images/flags/named/flag_kz.png" width="50" height="50" /> | :flag_kz: | Kazakhstan | kk, ru |
| <img src="/assets/images/flags/named/flag_ke.png" width="50" height="50" /> | :flag_ke: | Kenya | en, sw |
| <img src="/assets/images/flags/named/flag_ki.png" width="50" height="50" /> | :flag_ki: | Kiribati | en |
| <img src="/assets/images/flags/named/flag_kr.png" width="50" height="50" /> | :flag_kr: | South Korea | ko |
| <img src="/assets/images/flags/named/flag_kw.png" width="50" height="50" /> | :flag_kw: | Kuwait | ar |
| <img src="/assets/images/flags/named/flag_kg.png" width="50" height="50" /> | :flag_kg: | Kyrgyzstan | ky, ru |
| <img src="/assets/images/flags/named/flag_la.png" width="50" height="50" /> | :flag_la: | Lao People's Democratic Republic | lo |
| <img src="/assets/images/flags/named/flag_lv.png" width="50" height="50" /> | :flag_lv: | Latvia | lv |
| <img src="/assets/images/flags/named/flag_lb.png" width="50" height="50" /> | :flag_lb: | Lebanon | ar |
| <img src="/assets/images/flags/named/flag_ls.png" width="50" height="50" /> | :flag_ls: | Lesotho | st, en |
| <img src="/assets/images/flags/named/flag_lr.png" width="50" height="50" /> | :flag_lr: | Liberia | en |
| <img src="/assets/images/flags/named/flag_ly.png" width="50" height="50" /> | :flag_ly: | Libya | ar |
| <img src="/assets/images/flags/named/flag_li.png" width="50" height="50" /> | :flag_li: | Liechtenstein | de |
| <img src="/assets/images/flags/named/flag_lt.png" width="50" height="50" /> | :flag_lt: | Lithuania | lt |
| <img src="/assets/images/flags/named/flag_lu.png" width="50" height="50" /> | :flag_lu: | Luxembourg | lb, fr, de |
| <img src="/assets/images/flags/named/flag_mo.png" width="50" height="50" /> | :flag_mo: | Macao | zh-tw, pt |
| <img src="/assets/images/flags/named/flag_mk.png" width="50" height="50" /> | :flag_mk: | Macedonia | mk |
| <img src="/assets/images/flags/named/flag_mg.png" width="50" height="50" /> | :flag_mg: | Madagascar | mg, fr |
| <img src="/assets/images/flags/named/flag_mw.png" width="50" height="50" /> | :flag_mw: | Malawi | en |
| <img src="/assets/images/flags/named/flag_my.png" width="50" height="50" /> | :flag_my: | Malaysia | ms |
| <img src="/assets/images/flags/named/flag_mv.png" width="50" height="50" /> | :flag_mv: | Maldives | dv |
| <img src="/assets/images/flags/named/flag_ml.png" width="50" height="50" /> | :flag_ml: | Mali | fr |
| <img src="/assets/images/flags/named/flag_mt.png" width="50" height="50" /> | :flag_mt: | Malta | mt |
| <img src="/assets/images/flags/named/flag_mh.png" width="50" height="50" /> | :flag_mh: | Marshall Islands | mh, en |
| <img src="/assets/images/flags/named/flag_mq.png" width="50" height="50" /> | :flag_mq: | Martinique | fr |
| <img src="/assets/images/flags/named/flag_mr.png" width="50" height="50" /> | :flag_mr: | Mauritania | ar |
| <img src="/assets/images/flags/named/flag_mu.png" width="50" height="50" /> | :flag_mu: | Mauritius | en, fr |
| <img src="/assets/images/flags/named/flag_yt.png" width="50" height="50" /> | :flag_yt: | Mayotte | fr |
| <img src="/assets/images/flags/named/flag_mx.png" width="50" height="50" /> | :flag_mx: | Mexico | es |
| <img src="/assets/images/flags/named/flag_fm.png" width="50" height="50" /> | :flag_fm: | Micronesia | en |
| <img src="/assets/images/flags/named/flag_md.png" width="50" height="50" /> | :flag_md: | Moldova | ro |
| <img src="/assets/images/flags/named/flag_mc.png" width="50" height="50" /> | :flag_mc: | Monaco | fr |
| <img src="/assets/images/flags/named/flag_mn.png" width="50" height="50" /> | :flag_mn: | Mongolia | mn |
| <img src="/assets/images/flags/named/flag_me.png" width="50" height="50" /> | :flag_me: | Montenegro | cnr |
| <img src="/assets/images/flags/named/flag_ms.png" width="50" height="50" /> | :flag_ms: | Montserrat | en |
| <img src="/assets/images/flags/named/flag_ma.png" width="50" height="50" /> | :flag_ma: | Morocco | ar |
| <img src="/assets/images/flags/named/flag_mz.png" width="50" height="50" /> | :flag_mz: | Mozambique | pt |
| <img src="/assets/images/flags/named/flag_mm.png" width="50" height="50" /> | :flag_mm: | Myanmar | my |
| <img src="/assets/images/flags/named/flag_na.png" width="50" height="50" /> | :flag_na: | Namibia | en |
| <img src="/assets/images/flags/named/flag_nr.png" width="50" height="50" /> | :flag_nr: | Nauru | na |
| <img src="/assets/images/flags/named/flag_np.png" width="50" height="50" /> | :flag_np: | Nepal | ne |
| <img src="/assets/images/flags/named/flag_nl.png" width="50" height="50" /> | :flag_nl: | Netherlands | nl |
| <img src="/assets/images/flags/named/flag_an.png" width="50" height="50" /> | :flag_an: | Netherlands Antilles | nl |
| <img src="/assets/images/flags/named/flag_nc.png" width="50" height="50" /> | :flag_nc: | New Caledonia | fr |
| <img src="/assets/images/flags/named/flag_nz.png" width="50" height="50" /> | :flag_nz: | New Zealand | en |
| <img src="/assets/images/flags/named/flag_ni.png" width="50" height="50" /> | :flag_ni: | Nicaragua | es |
| <img src="/assets/images/flags/named/flag_ne.png" width="50" height="50" /> | :flag_ne: | Niger | fr |
| <img src="/assets/images/flags/named/flag_ng.png" width="50" height="50" /> | :flag_ng: | Nigeria | en |
| <img src="/assets/images/flags/named/flag_nu.png" width="50" height="50" /> | :flag_nu: | Niue | en, niu |
| <img src="/assets/images/flags/named/flag_nf.png" width="50" height="50" /> | :flag_nf: | Norfolk Island | en |
| <img src="/assets/images/flags/named/flag_mp.png" width="50" height="50" /> | :flag_mp: | Northern Mariana Islands | en, ch, cal |
| <img src="/assets/images/flags/named/flag_no.png" width="50" height="50" /> | :flag_no: | Norway | no |
| <img src="/assets/images/flags/named/flag_om.png" width="50" height="50" /> | :flag_om: | Oman | ar |
| <img src="/assets/images/flags/named/flag_pk.png" width="50" height="50" /> | :flag_pk: | Pakistan | ur |
| <img src="/assets/images/flags/named/flag_pw.png" width="50" height="50" /> | :flag_pw: | Palau | en, pau |
| <img src="/assets/images/flags/named/flag_ps.png" width="50" height="50" /> | :flag_ps: | Palestinian Territory | ar |
| <img src="/assets/images/flags/named/flag_pa.png" width="50" height="50" /> | :flag_pa: | Panama | es |
| <img src="/assets/images/flags/named/flag_pg.png" width="50" height="50" /> | :flag_pg: | Papua New Guinea | en, ho, tpi |
| <img src="/assets/images/flags/named/flag_py.png" width="50" height="50" /> | :flag_py: | Paraguay | es, gug |
| <img src="/assets/images/flags/named/flag_pe.png" width="50" height="50" /> | :flag_pe: | Peru | es |
| <img src="/assets/images/flags/named/flag_ph.png" width="50" height="50" /> | :flag_ph: | Philippines | tl |
| <img src="/assets/images/flags/named/flag_pn.png" width="50" height="50" /> | :flag_pn: | Pitcairn | en |
| <img src="/assets/images/flags/named/flag_pl.png" width="50" height="50" /> | :flag_pl: | Poland | pl |
| <img src="/assets/images/flags/named/flag_pt.png" width="50" height="50" /> | :flag_pt: | Portugal | pt |
| <img src="/assets/images/flags/named/flag_pr.png" width="50" height="50" /> | :flag_pr: | Puerto Rico | es |
| <img src="/assets/images/flags/named/flag_qa.png" width="50" height="50" /> | :flag_qa: | Qatar | ar |
| <img src="/assets/images/flags/named/flag_re.png" width="50" height="50" /> | :flag_re: | Reunion | fr |
| <img src="/assets/images/flags/named/flag_ro.png" width="50" height="50" /> | :flag_ro: | Romania | ro |
| <img src="/assets/images/flags/named/flag_ru.png" width="50" height="50" /> | :flag_ru: | Russian Federation | ru |
| <img src="/assets/images/flags/named/flag_rw.png" width="50" height="50" /> | :flag_rw: | Rwanda | rw, en, fr, sw |
| <img src="/assets/images/flags/named/flag_bl.png" width="50" height="50" /> | :flag_bl: | Saint Barthelemy | fr |
| <img src="/assets/images/flags/named/flag_sh.png" width="50" height="50" /> | :flag_sh: | Saint Helena | en |
| <img src="/assets/images/flags/named/flag_kn.png" width="50" height="50" /> | :flag_kn: | Saint Kitts And Nevis | en |
| <img src="/assets/images/flags/named/flag_lc.png" width="50" height="50" /> | :flag_lc: | Saint Lucia | en |
| <img src="/assets/images/flags/named/flag_mf.png" width="50" height="50" /> | :flag_mf: | Saint Martin | nl, fr |
| <img src="/assets/images/flags/named/flag_pm.png" width="50" height="50" /> | :flag_pm: | Saint Pierre And Miquelon | fr |
| <img src="/assets/images/flags/named/flag_vc.png" width="50" height="50" /> | :flag_vc: | Saint Vincent And Grenadines | en |
| <img src="/assets/images/flags/named/flag_ws.png" width="50" height="50" /> | :flag_ws: | Samoa | sm, en |
| <img src="/assets/images/flags/named/flag_sm.png" width="50" height="50" /> | :flag_sm: | San Marino | it |
| <img src="/assets/images/flags/named/flag_st.png" width="50" height="50" /> | :flag_st: | Sao Tome and Principe | pt |
| <img src="/assets/images/flags/named/flag_sa.png" width="50" height="50" /> | :flag_sa: | Saudi Arabia | ar |
| <img src="/assets/images/flags/named/flag_sn.png" width="50" height="50" /> | :flag_sn: | Senegal | fr |
| <img src="/assets/images/flags/named/flag_rs.png" width="50" height="50" /> | :flag_rs: | Serbia | sr |
| <img src="/assets/images/flags/named/flag_sc.png" width="50" height="50" /> | :flag_sc: | Seychelles | en, fr |
| <img src="/assets/images/flags/named/flag_sl.png" width="50" height="50" /> | :flag_sl: | Sierra Leone | en |
| <img src="/assets/images/flags/named/flag_sg.png" width="50" height="50" /> | :flag_sg: | Singapore | en, ta, zh-tw, ms |
| <img src="/assets/images/flags/named/flag_sk.png" width="50" height="50" /> | :flag_sk: | Slovakia | sk |
| <img src="/assets/images/flags/named/flag_si.png" width="50" height="50" /> | :flag_si: | Slovenia | sl |
| <img src="/assets/images/flags/named/flag_sb.png" width="50" height="50" /> | :flag_sb: | Solomon Islands | en |
| <img src="/assets/images/flags/named/flag_so.png" width="50" height="50" /> | :flag_so: | Somalia | so, ar |
| <img src="/assets/images/flags/named/flag_za.png" width="50" height="50" /> | :flag_za: | South Africa | en, af, st, xh, zu |
| <img src="/assets/images/flags/named/flag_gs.png" width="50" height="50" /> | :flag_gs: | South Georgia And Sandwich Islands | en |
| <img src="/assets/images/flags/named/flag_es.png" width="50" height="50" /> | :flag_es: | Spain | es |
| <img src="/assets/images/flags/named/flag_lk.png" width="50" height="50" /> | :flag_lk: | Sri Lanka | si, ta |
| <img src="/assets/images/flags/named/flag_sd.png" width="50" height="50" /> | :flag_sd: | Sudan | ar |
| <img src="/assets/images/flags/named/flag_sr.png" width="50" height="50" /> | :flag_sr: | Suriname | nl |
| <img src="/assets/images/flags/named/flag_sj.png" width="50" height="50" /> | :flag_sj: | Svalbard And Jan Mayen | no |
| <img src="/assets/images/flags/named/flag_sz.png" width="50" height="50" /> | :flag_sz: | Swaziland | ss, en |
| <img src="/assets/images/flags/named/flag_se.png" width="50" height="50" /> | :flag_se: | Sweden | sv |
| <img src="/assets/images/flags/named/flag_ch.png" width="50" height="50" /> | :flag_ch: | Switzerland | de, fr, it, rm |
| <img src="/assets/images/flags/named/flag_sy.png" width="50" height="50" /> | :flag_sy: | Syrian Arab Republic | ar |
| <img src="/assets/images/flags/named/flag_tw.png" width="50" height="50" /> | :flag_tw: | Taiwan | zh-tw |
| <img src="/assets/images/flags/named/flag_tj.png" width="50" height="50" /> | :flag_tj: | Tajikistan | tg |
| <img src="/assets/images/flags/named/flag_tz.png" width="50" height="50" /> | :flag_tz: | Tanzania | sw |
| <img src="/assets/images/flags/named/flag_th.png" width="50" height="50" /> | :flag_th: | Thailand | th |
| <img src="/assets/images/flags/named/flag_tl.png" width="50" height="50" /> | :flag_tl: | Timor-Leste | tet, pt |
| <img src="/assets/images/flags/named/flag_tg.png" width="50" height="50" /> | :flag_tg: | Togo | fr |
| <img src="/assets/images/flags/named/flag_tk.png" width="50" height="50" /> | :flag_tk: | Tokelau | tkl, en |
| <img src="/assets/images/flags/named/flag_to.png" width="50" height="50" /> | :flag_to: | Tonga | to, en |
| <img src="/assets/images/flags/named/flag_tt.png" width="50" height="50" /> | :flag_tt: | Trinidad and Tobago | en |
| <img src="/assets/images/flags/named/flag_tn.png" width="50" height="50" /> | :flag_tn: | Tunisia | ar |
| <img src="/assets/images/flags/named/flag_tr.png" width="50" height="50" /> | :flag_tr: | Turkey | tr |
| <img src="/assets/images/flags/named/flag_tm.png" width="50" height="50" /> | :flag_tm: | Turkmenistan | tk |
| <img src="/assets/images/flags/named/flag_tc.png" width="50" height="50" /> | :flag_tc: | Turks and Caicos Islands | en |
| <img src="/assets/images/flags/named/flag_tv.png" width="50" height="50" /> | :flag_tv: | Tuvalu | tvl, en |
| <img src="/assets/images/flags/named/flag_ug.png" width="50" height="50" /> | :flag_ug: | Uganda | en, sw |
| <img src="/assets/images/flags/named/flag_ua.png" width="50" height="50" /> | :flag_ua: | Ukraine | uk |
| <img src="/assets/images/flags/named/flag_ae.png" width="50" height="50" /> | :flag_ae: | United Arab Emirates | ar |
| <img src="/assets/images/flags/named/flag_gb.png" width="50" height="50" /> | :flag_gb: | United Kingdom | en |
| <img src="/assets/images/flags/named/flag_us.png" width="50" height="50" /> | :flag_us: | United States | en |
| <img src="/assets/images/flags/named/flag_um.png" width="50" height="50" /> | :flag_um: | United States Outlying Islands | en |
| <img src="/assets/images/flags/named/flag_uy.png" width="50" height="50" /> | :flag_uy: | Uruguay | es, pt |
| <img src="/assets/images/flags/named/flag_uz.png" width="50" height="50" /> | :flag_uz: | Uzbekistan | uz |
| <img src="/assets/images/flags/named/flag_vu.png" width="50" height="50" /> | :flag_vu: | Vanuatu | bi, en, fr |
| <img src="/assets/images/flags/named/flag_ve.png" width="50" height="50" /> | :flag_ve: | Venezuela | es |
| <img src="/assets/images/flags/named/flag_vn.png" width="50" height="50" /> | :flag_vn: | Vietnam | vi |
| <img src="/assets/images/flags/named/flag_vg.png" width="50" height="50" /> | :flag_vg: | British Virgin Islands | en |
| <img src="/assets/images/flags/named/flag_vi.png" width="50" height="50" /> | :flag_vi: | Us Virgin Islands | en |
| <img src="/assets/images/flags/named/flag_wf.png" width="50" height="50" /> | :flag_wf: | Wallis and Futuna | fr |
| <img src="/assets/images/flags/named/flag_eh.png" width="50" height="50" /> | :flag_eh: | Western Sahara | ar |
| <img src="/assets/images/flags/named/flag_ye.png" width="50" height="50" /> | :flag_ye: | Yemen | ar |
| <img src="/assets/images/flags/named/flag_zm.png" width="50" height="50" /> | :flag_zm: | Zambia | en |
| <img src="/assets/images/flags/named/flag_zw.png" width="50" height="50" /> | :flag_zw: | Zimbabwe | ny, en, xh, st, sn |
