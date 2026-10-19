# ISTQB® CTFL® v4.0.1 — Türkçe Deneme Sınavı 2

## Sınav hakkında

Bu çalışma, İngilizce Deneme Sınavı 2 esas alınarak hazırlanmıştır. Soru ve seçenekler önce İngilizce (EN), hemen altında Türkçe (TR) verilir; açıklamalar Türkçedir. İki dil aynı soruyu ve aynı seçenekleri gösterir; her soru için tek cevap işaretleyin. 40 soru, dört seçenek ve her soruda tek doğru cevap vardır. Her soru 1 puandır; geçme çizgisi 26/40 (%65), standart süre 60 dakikadır.

**Süreyi doğru seçin.** TTB'nin Türkçe/İngilizce kitapçığıyla sınava giren ana dili Türkçe aday için süre 60 dakikadır. Ana dili Türkçe olmayan aday için TTB 75 dakika belirtir. Ek süre sınav dili ve sağlayıcı koşullarına bağlıdır. Sınava kaydolmadan önce [TTB'nin güncel koşullarını](https://www.turkishtestingboard.org/kayit/foundation-level-certified-tester/) kontrol edin.

| Bilişsel seviye | Soru |
|---|---:|
| K1 — Hatırlama | 8 |
| K2 — Anlama | 24 |
| K3 — Uygulama | 8 |

| Bölüm | Soru |
|---|---:|
| 1 — Yazılım testinin temelleri | 8 |
| 2 — Yaşam döngüsü boyunca test | 6 |
| 3 — Statik test | 4 |
| 4 — Test analizi ve tasarımı | 11 |
| 5 — Test aktivitelerinin yönetimi | 9 |
| 6 — Test araçları | 2 |

### Nasıl kullanılır?

Gerçek sınav provası için 60 dakikalık, kesintisiz bir oturum ayırın. Ek süre hakkınız varsa 75 dakika seçin; 75 dakikayı bir çalışma süresi olarak da kullanabilirsiniz, ancak bunu 60 dakikalık prova sonucuyla aynı ölçüm saymayın. Sorular sınav provası için karışık sıradadır; bölüm başlıklarına göre gruplanmamıştır. Cevaplara bakmadan 40 soruyu tamamlayın, Part 2 ile puanlayın, ardından Part 3 ile yanlışların nedenlerini inceleyin.

Her soru için bir seçenek işaretleyin. Yanlış veya boş cevap 0 puandır; yanlışlar doğruları götürmez. K3 sorular için yaklaşık üçer dakika ayırmak bir çalışma önerisidir; bütün sınavın toplam süresini de gözetin.

### Dört tuzak

- **Kaynak bilgi eksiği:** Ders programındaki bir kavramı, tanımı veya listeyi hatırlayamama. İlgili bölümü yeniden çalışın.
- **Near-miss karışıklığı:** Komşu kavramları birbirinin yerine koyma; örneğin onaylama ve regresyon testi. Ayırt edici amaçlarını karşılaştırın.
- **Prosedür hatası:** Bir tekniği uygularken yanlış adım, varyant veya hesap kullanma. Çözümü adım adım yeniden kurun.
- **Dikkatsiz okuma:** Kökün yönlendirmesini veya verisini kaçırma. **EN İYİ** ve **DEĞİLDİR** gibi yön sözcüklerini kontrol edin.

Bu dört etiket sorunun genel tuzağını gösterir. Kılavuzdaki çeldirici adları ise tek bir yanlış seçeneğin neden cazip olduğunu açıklar; iki sınıflandırma farklı amaçlara hizmet eder.

**Bağımsızlık ve lisans.** ISTQB® ve CTFL® tescilli markalardır. Bu çalışma ISTQB veya TTB tarafından onaylanmamıştır ve bu kuruluşların resmî sınavı değildir. © 2026 Kadir Çamoğlu. Özgün içerik [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) ile paylaşılır; ISTQB'ye ait alıntılar, LO kodları, ilke adları ve markalar bu lisansın dışındadır.


## Part 1 — Sorular

Cevap anahtarını açmadan önce bütün soruları tamamlayın.

### S1–S10



**Soru 1** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A discount service uses the following five feasible rules. The tiers are S = Standard, G = Gold and P = Platinum. D = true and Y = false. A dash means that the coupon value does not affect that rule. For coverage, use the five columns as listed without merging them.

| Condition / action | R1 | R2 | R3 | R4 | R5 |
|---|---|---|---|---|---|
| Customer tier | S | G | G | P | P |
| Valid coupon | – | D | Y | D | Y |
| 0% discount | X | – | – | – | – |
| 20% discount | – | X | – | – | – |
| 10% discount | – | – | X | – | – |
| 30% discount | – | – | – | X | – |
| 15% discount | – | – | – | – | X |

The executed tests use (Standard, D), (Gold, D), (Standard, Y) and (Gold, D). What is the smallest number of additional test cases needed to reach 100% coverage of the listed rules?

a) 1

b) 3

c) 2

d) 5

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir indirim servisi aşağıdaki beş uygulanabilir kuralı kullanır. S = Standart, G = Altın, P = Platin; D = doğru, Y = yanlış. Kupon koşulundaki “–”, bu koşulun kuralı etkilemediğini gösterir. Kapsam hesabında sütunları birleştirmeden aşağıdaki beş kuralı kullanın.

| Koşul / aksiyon | R1 | R2 | R3 | R4 | R5 |
|---|---|---|---|---|---|
| Müşteri seviyesi | S | G | G | P | P |
| Geçerli kupon | – | D | Y | D | Y |
| %0 indirim | X | – | – | – | – |
| %20 indirim | – | X | – | – | – |
| %10 indirim | – | – | X | – | – |
| %30 indirim | – | – | – | X | – |
| %15 indirim | – | – | – | – | X |

Koşulan testler (Standart, D), (Altın, D), (Standart, Y) ve (Altın, D) girdilerini kullanır. Listelenen kurallarda %100 kapsama ulaşmak için en az kaç ek test senaryosu gerekir?

a) 1

b) 3

c) 2

d) 5

</div>



**Soru 2** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

At the end of a release, the team archives the test environment configuration and the testware, hands selected regression tests over to the maintenance team, and analyzes lessons learned to improve future testing. Which test activity does this describe?

a) Test completion

b) Test monitoring and control

c) Test implementation

d) Test planning

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir sürümün testleri bittikten sonra ekip, test ortamı ayarlarını ve test çalışma ürünlerini arşivler, seçilen regresyon testlerini bakım ekibine devreder ve sonraki çalışmaları iyileştirmek için çıkarılan dersleri değerlendirir. Hangi test aktivitesi anlatılmaktadır?

a) Test tamamlama

b) Test gözetimi ve kontrolü

c) Test uyarlama

d) Test planlama

</div>



**Soru 3** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Which of the following is a potential benefit of test automation?

a) It covers business needs beyond those represented in the automated checks

b) It removes the effort required to maintain testware after product changes

c) It makes the quality of results independent of the automated test design

d) It enables more objective comparisons of the results of repeated checks

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Aşağıdakilerden hangisi test otomasyonunun sağlayabileceği bir faydadır?

a) Otomatik kontrollerde temsil edilmeyen iş ihtiyaçlarının kapsamını da sağlaması

b) Ürün değişikliklerinden sonra test çalışma ürünlerinin bakım gereksinimini kaldırması

c) Sonuçların kalitesini otomatik testlerin tasarımından bağımsız hâle getirmesi

d) Tekrarlanan kontrollerin sonuçlarını daha nesnel biçimde karşılaştırmayı sağlaması

</div>



**Soru 4** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

An order system starts in the New state. The following transitions are defined; any transition not listed is invalid.

<svg xmlns="http://www.w3.org/2000/svg" width="320" height="420" viewBox="0 0 320 420" role="img" aria-label="Order state diagram: New, Paid, Shipped, Delivered and Cancelled. All transitions are also listed in the table below." style="max-width:100%;height:auto;display:block;margin:1rem auto;color:inherit"><defs><marker id="m2-en-arrow" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 Z" fill="currentColor"/></marker></defs><g fill="none" stroke="currentColor" stroke-width="1.5"><rect x="12" y="35" width="135" height="42" rx="8"/><rect x="12" y="135" width="135" height="42" rx="8"/><rect x="12" y="235" width="135" height="42" rx="8"/><rect x="12" y="335" width="135" height="42" rx="8"/><rect x="186" y="190" width="127" height="42" rx="8"/><g marker-end="url(#m2-en-arrow)"><path d="M80 15 V33"/><path d="M80 78 V133"/><path d="M80 178 V233"/><path d="M80 278 V333"/><path d="M148 56 H250 V187"/><path d="M148 156 L185 207"/></g></g><circle cx="80" cy="10" r="5" fill="currentColor"/><g fill="currentColor" font-family="system-ui,sans-serif" font-size="14" text-anchor="middle"><text x="80" y="61">New</text><text x="80" y="161">Paid</text><text x="80" y="261">Shipped</text><text x="80" y="361">Delivered</text><text x="250" y="216">Cancelled</text><text x="103" y="111">pay</text><text x="112" y="211">ship</text><text x="113" y="311">deliver</text><text x="280" y="117">cancel</text><text x="184" y="168">cancel</text></g></svg>

| Initial state | Event | Next state |
|---|---|---|
| New | pay | Paid |
| New | cancel | Cancelled |
| Paid | ship | Shipped |
| Paid | cancel | Cancelled |
| Shipped | deliver | Delivered |

Text model: New —pay→ Paid —ship→ Shipped —deliver→ Delivered. From New and Paid, the cancel event leads to Cancelled. There are no outgoing transitions from Cancelled or Delivered.

The team wants a negative test case that attempts an invalid transition. Which event sequence, starting in New, has an **invalid final step**?

a) pay, ship, deliver

b) pay, cancel

c) cancel

d) pay, ship, cancel

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir sipariş sisteminde başlangıç durumu Yeni’dir. Tanımlanan geçişler aşağıdaki gibidir; listelenmeyen bir geçiş geçersizdir.

<svg xmlns="http://www.w3.org/2000/svg" width="320" height="420" viewBox="0 0 320 420" role="img" aria-label="Sipariş durum diyagramı: Yeni, Ödendi, Gönderildi, Teslim edildi ve İptal edildi. Bütün geçişler aşağıdaki tabloda da verilir." style="max-width:100%;height:auto;display:block;margin:1rem auto;color:inherit"><defs><marker id="m2-arrow" markerWidth="8" markerHeight="8" refX="7" refY="4" orient="auto"><path d="M0 0 L8 4 L0 8 Z" fill="currentColor"/></marker></defs><g fill="none" stroke="currentColor" stroke-width="1.5"><rect x="12" y="35" width="135" height="42" rx="8"/><rect x="12" y="135" width="135" height="42" rx="8"/><rect x="12" y="235" width="135" height="42" rx="8"/><rect x="12" y="335" width="135" height="42" rx="8"/><rect x="186" y="190" width="127" height="42" rx="8"/><g marker-end="url(#m2-arrow)"><path d="M80 15 V33"/><path d="M80 78 V133"/><path d="M80 178 V233"/><path d="M80 278 V333"/><path d="M148 56 H250 V187"/><path d="M148 156 L185 207"/></g></g><circle cx="80" cy="10" r="5" fill="currentColor"/><g fill="currentColor" font-family="system-ui,sans-serif" font-size="14" text-anchor="middle"><text x="80" y="61">Yeni</text><text x="80" y="161">Ödendi</text><text x="80" y="261">Gönderildi</text><text x="80" y="361">Teslim edildi</text><text x="250" y="216">İptal edildi</text><text x="103" y="111">öde</text><text x="112" y="211">gönder</text><text x="113" y="311">teslim et</text><text x="280" y="117">iptal et</text><text x="184" y="168">iptal et</text></g></svg>

| Başlangıç durumu | Olay | Sonraki durum |
|---|---|---|
| Yeni | öde | Ödendi |
| Yeni | iptal et | İptal edildi |
| Ödendi | gönder | Gönderildi |
| Ödendi | iptal et | İptal edildi |
| Gönderildi | teslim et | Teslim edildi |

Metinsel model: Yeni —öde→ Ödendi —gönder→ Gönderildi —teslim et→ Teslim edildi. Yeni ve Ödendi durumlarından “iptal et” olayıyla İptal edildi durumuna geçilebilir. İptal edildi ve Teslim edildi durumlarından çıkış yoktur.

Ekip geçersiz bir geçişi deneyecek negatif test senaryosu istemektedir. Yeni durumundan başlayan hangi olay dizisinin **son adımı geçersizdir**?

a) öde, gönder, teslim et

b) öde, iptal et

c) iptal et

d) öde, gönder, iptal et

</div>



**Soru 5** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A shared test environment has been baselined. A tester needs to change a configuration setting for an investigation, and other teams must be able to identify the setup used for each result. Which action supports configuration management?

a) Overwrite the shared setting and use the investigation notes as the version history

b) Put the setting change through change control and assign a configuration version

c) Keep the existing configuration identifier while changing the setting for the next run

d) Discard the old configuration once the changed environment has produced a result

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Paylaşılan bir test ortamı için temel çizgi (baseline) oluşturulmuştur. Bir test uzmanı inceleme amacıyla bir ayarı değiştirmek ister; diğer ekipler de her test sonucunda hangi ortamın kullanıldığını belirleyebilmelidir. Hangi işlem yapılandırma yönetimini (configuration management) destekler?

a) Ortak ayarın üzerine yazıp inceleme notlarını sürüm geçmişi olarak kullanmak

b) Ayarı değişiklik kontrolünden geçirip yapılandırmaya sürüm vermek

c) Sonraki koşumda ayarı değiştirirken mevcut yapılandırma kimliğini korumak

d) Değişen ortamdan sonuç alındığında önceki yapılandırmayı kayıttan çıkarmak

</div>



**Soru 6** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Which measure helps review participants who are unfamiliar with their assigned review roles?

a) Give each participant a larger section so that practice replaces preparation

b) Use the findings to compare participants' individual productivity

c) Provide suitable training so that participants can perform their roles

d) Choose a more formal review type as a substitute for preparing participants

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Gözden geçirmede kendilerine verilen rolleri tanımayan katılımcılara hangi önlem yardımcı olur?

a) Hazırlığın yerini uygulama alsın diye her katılımcıya daha büyük bir bölüm vermek

b) Bulguları katılımcıların bireysel üretkenliğini karşılaştırmak için kullanmak

c) Katılımcılara rollerini yerine getirebilmeleri için uygun eğitim vermek

d) Katılımcıları hazırlamak yerine daha resmî bir gözden geçirme türü seçmek

</div>



**Soru 7** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Which change increases a risk level, assuming the other contributing factor remains unchanged?

a) Increased likelihood with impact held constant

b) Reduced likelihood with impact held constant

c) Reduced impact with likelihood held constant

d) Unchanged likelihood and unchanged impact

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Diğer katkı faktörü değişmeden kaldığında hangi değişiklik risk seviyesini artırır?

a) Etki sabitken olasılığın artması

b) Etki sabitken olasılığın azalması

c) Olasılık sabitken etkinin azalması

d) Olasılığın ve etkinin değişmemesi

</div>



**Soru 8** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

In test-driven development, which artifact is created first to guide the next small change to the code?

a) An executable test for a small unit of behavior

b) A narrative scenario agreed with business representatives

c) A defect report describing a failure in the released product

d) An execution log from the completed system test run

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Test güdümlü yazılım geliştirmede (TDD), koddaki bir sonraki küçük değişikliğe yön vermek için önce hangi iş ürünü oluşturulur?

a) Küçük bir davranış birimi için çalıştırılabilir test

b) İş temsilcileriyle kararlaştırılmış anlatı biçiminde senaryo

c) Yayımlanan üründeki arızayı açıklayan hata raporu

d) Tamamlanmış sistem testinin koşum kaydı

</div>



**Soru 9** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team divides all the testing work for a small release into two tasks. Experts provide these estimates in person-hours: a = optimistic, m = most likely, b = pessimistic.

| Task | a | m | b |
|---|---|---|---|
| Import checks | 3 | 7 | 17 |
| Notification checks | 5 | 9 | 25 |

The team has allocated 20 person-hours for the two tasks together. Using three-point estimation for each task, which total required test effort and comparison with the allocation are correct? Use exact values; do not round intermediate results.

a) 22 person-hours in total, exceeding the allocation by 2

b) 19 person-hours in total, leaving 1 of the allocation

c) 16 person-hours in total, leaving 4 of the allocation

d) 11 person-hours in total, leaving 9 of the allocation

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip, küçük bir sürümün bütün test işlerini iki göreve ayırır. Uzmanların kişi-saat cinsinden tahminleri aşağıdadır: a = iyimser, m = en olası, b = kötümser.

| Görev | a | m | b |
|---|---:|---:|---:|
| İçe aktarma kontrolleri | 3 | 7 | 17 |
| Bildirim kontrolleri | 5 | 9 | 25 |

İki görevin toplamı için 20 kişi-saat ayrılmıştır. Her görev için **üç noktalı tahminleme** (three-point estimation) uygulandığında toplam test eforu ve ayrılan eforla karşılaştırması hangisidir? Hesabı tam değerlerle yapın; ara sonuçları yuvarlamayın.

a) Toplam 22 kişi-saat; ayrılan efor 2 kişi-saat aşılır.

b) Toplam 19 kişi-saat; ayrılan efordan 1 kişi-saat kalır.

c) Toplam 16 kişi-saat; ayrılan efordan 4 kişi-saat kalır.

d) Toplam 11 kişi-saat; ayrılan efordan 9 kişi-saat kalır.

</div>



**Soru 10** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A new team member classifies an automated component check and an automated business acceptance check as Q1 because both are automated. What is the problem with this use of the testing quadrants?

a) The quadrants distinguish perspective and purpose; the two checks need not share a quadrant

b) The quadrants distinguish the language used for automation; both checks need different tools

c) The quadrants distinguish when checks were written; both checks must follow implementation

d) The quadrants distinguish the people running the checks; both checks need separate testers

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Yeni bir ekip üyesi, otomatik bir bileşen kontrolünü ve otomatik bir iş kabul kontrolünü ikisi de otomatik olduğu için Q1’e yerleştirir. Test çeyreklerinin (testing quadrants) bu kullanımındaki sorun nedir?

a) Çeyrekler bakış açısı ve amacı ayırır; bu iki kontrol aynı çeyrekte olmak zorunda değildir.

b) Çeyrekler otomasyon dilini ayırır; bu iki kontrol farklı araçlarla çalıştırılmak zorundadır.

c) Çeyrekler testin yazıldığı zamanı ayırır; bu iki kontrol kodlamadan sonra hazırlanmalıdır.

d) Çeyrekler testleri koşan kişileri ayırır; bu iki kontrol ayrı test uzmanları gerektirir.

</div>


### S11–S20



**Soru 11** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A test plan describes the scope, approach and schedule, but stakeholders disagree about how they will receive progress information. Which addition belongs in the plan to address that gap?

a) The detailed pass/fail log from each individual test run

b) The exact commands used to execute each individual test

c) The recipients, formats and frequency of status updates

d) The completed investigation of each reported anomaly

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Test planında kapsam, yaklaşım ve takvim açıklanmıştır; ancak paydaşlar ilerleme bilgilerini nasıl alacakları konusunda anlaşamamaktadır. Bu boşluğu gidermek için plana ne eklenmelidir?

a) Her bir test koşumundan gelen ayrıntılı geçti/kaldı kayıtları

b) Her bir testi çalıştırmak için kullanılan komutların tamamı

c) Durum bildirimlerinin alıcıları, biçimleri ve sıklığı

d) Bildirilen her anomali için tamamlanmış inceleme sonuçları

</div>



**Soru 12** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A comparison service accepts any integer. It returns LOW for an input below 37, MATCH for 37, and HIGH for an input above 37. Applying 3-value boundary value analysis across all three partitions, how many distinct input values are needed for full coverage?

a) 3

b) 9

c) 5

d) 8

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir karşılaştırma servisi her tam sayıyı kabul eder. Girdi 37’den küçükse LOW, 37 ise MATCH, 37’den büyükse HIGH döndürür. Üç payın tamamında **3 değerli sınır değer analizi** (boundary value analysis) uygulandığında tam kapsam için kaç farklı girdi değeri gerekir?

a) 3

b) 9

c) 5

d) 8

</div>



**Soru 13** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A release's product risk has increased, and its existing test schedule no longer looks adequate. The testing role is revising the test conditions. Which additional task belongs mainly to the test management role?

a) Ranking the revised test conditions according to the product risks they address

b) Assessing whether the test basis is detailed enough to design the revised cases

c) Checking the prepared environment against the revised environment requirements

d) Agreeing a revised test scope and resource allocation with the relevant stakeholders

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir sürümün ürün riski artmış ve mevcut test takvimi yetersiz görünmeye başlamıştır. Test rolünü üstlenenler test koşullarını yeniden ele almaktadır. Aşağıdaki ek görevlerden hangisi ağırlıklı olarak test yönetimi rolüne aittir?

a) Güncellenen test koşullarını ele aldıkları ürün risklerine göre sıralamak

b) Test esasının yeni senaryoları tasarlamaya yeterli ayrıntı taşıyıp taşımadığını değerlendirmek

c) Hazırlanan ortamın güncellenmiş test ortamı gereksinimlerini karşılayıp karşılamadığını kontrol etmek

d) Yeni test kapsamını ve kaynak dağılımını ilgili paydaşlarla kararlaştırmak

</div>



**Soru 14** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A user story has the acceptance criterion: "Registered customers who enter a valid promo code receive a 15% discount; an invalid or expired code (the system treats both as the same rejected-code case) must show an error message and charge the full price." The customer is registered in every test. Following ATDD, which set of test cases MOST completely covers this acceptance criterion?

a) TC1: valid code entered → the 15% discount is applied to the order total at checkout

b) TC1: valid code → 15% discount is applied; TC2: expired code → error message shown and the full price charged

c) TC1: expired code → an error message is shown; TC2: invalid code → an error message is shown

d) TC1: valid code → 15% discount is applied; TC2: valid code → the discount is stored in the order database

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir kullanıcı hikâyesinin kabul kriteri şöyledir: “Kayıtlı müşteri geçerli promosyon kodu girerse %15 indirim alır. Geçersiz veya süresi dolmuş kodda hata mesajı gösterilir ve tam fiyat alınır.” Sistem geçersiz ve süresi dolmuş kodları aynı reddedilen-kod durumu olarak işler. Bütün testlerde müşteri kayıtlıdır. Kabul testi güdümlü yazılım geliştirme (ATDD) kapsamında hangi test kümesi kriterin belirtilen davranışlarını **EN EKSİKSİZ** kapsar?

a) TC1: Geçerli kodla ödeme adımında sipariş toplamına %15 indirim uygulandığını kontrol et.

b) TC1: Geçerli kod → %15 indirim; TC2: Süresi dolmuş kod → hata mesajı ve tam fiyat.

c) TC1: Süresi dolmuş kod → hata mesajı; TC2: Geçersiz kod → hata mesajı gösterimi.

d) TC1: Geçerli kod → %15 indirim; TC2: Geçerli kod → indirimin veri tabanında saklanması.

</div>



**Soru 15** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A tester configures a service-call tool, reads request and response logs, and uses database queries to investigate an inconsistent result. Which generic skill most directly enables this work?

a) Domain knowledge of the business policies that determine the expected outcome

b) Communication skills for presenting the investigation to business stakeholders

c) Technical knowledge for using the tools and understanding the system's interfaces

d) Teamwork skills for sharing responsibility for the investigation's outcome

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir test uzmanı servis çağrısı aracını yapılandırır, istek ve yanıt kayıtlarını okur ve tutarsız bir sonucu incelemek için veri tabanı sorguları kullanır. Bu işi en doğrudan hangi genel beceri mümkün kılar?

a) Beklenen sonucu belirleyen iş kurallarına ilişkin alan bilgisi

b) İncelemeyi iş paydaşlarına aktarmaya yönelik iletişim becerisi

c) Araçları ve sistem arayüzlerini kullanmaya yönelik teknik bilgi

d) İnceleme sorumluluğunu paylaşmaya yönelik ekip çalışması becerisi

</div>



**Soru 16** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

After an exploratory session, stakeholders ask which paths the tester followed and what was discovered. The tester proposes recording this information on a session sheet for the debriefing. How does this fit exploratory testing?

a) It turns the session into scripted testing because documenting steps fixes them in advance

b) It replaces the need to evaluate results while exploring the test object

c) It records the exploration and findings so they can be discussed after the session

d) It establishes that every area in the test object was exercised during the session

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir keşif testi oturumundan sonra paydaşlar test uzmanının hangi yolları izlediğini ve neler bulduğunu sorar. Uzman bu bilgileri oturum sonrası değerlendirme için test oturum formuna kaydetmeyi önerir. Bu öneri keşif testiyle (exploratory testing) nasıl ilişkilidir?

a) Adımları belgelemek onları önceden sabitlediği için oturumu betikli teste dönüştürür.

b) Test nesnesi keşfedilirken sonuçları değerlendirme gereksiniminin yerini alır.

c) Keşfedilen yolları ve bulguları oturum sonrasında görüşülebilecek biçimde kaydeder.

d) Oturum sırasında test nesnesinin her alanının çalıştırıldığını ortaya koyar.

</div>



**Soru 17** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

How can information obtained from testing contribute to quality assurance?

a) By making the test team responsible for correcting the faults it reports

b) By helping the organization improve the processes used to develop software

c) By replacing process assessments with the pass rates of the executed tests

d) By establishing that a tested release satisfies every future user's needs

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Testten elde edilen bilgiler kalite güvencesine (quality assurance) nasıl katkıda bulunabilir?

a) Bildirdiği hataların düzeltilmesini test ekibinin sorumluluğuna vererek

b) Yazılım geliştirme süreçlerinin iyileştirilmesine girdi sağlayarak

c) Süreç değerlendirmelerinin yerine testlerin geçme oranını koyarak

d) Sınanan sürümün gelecekteki bütün kullanıcı ihtiyaçlarını karşıladığını kanıtlayarak

</div>



**Soru 18** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

What can testers contribute to colleagues through close cooperation in the whole team approach?

a) Testing knowledge that helps influence how the product is developed

b) Authority to approve the business priorities on behalf of the product owner

c) A transfer of the developers' implementation duties to the testers

d) A separation of quality discussions from the team's development decisions

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Tüm ekip yaklaşımında (whole team approach) yakın iş birliği yapan test uzmanları, diğer ekip üyelerine hangi katkıyı sunabilir?

a) Ürünün geliştirilme biçimini etkileyen test bilgisini paylaşmak

b) Ürün sahibi adına iş önceliklerini onaylama yetkisini üstlenmek

c) Geliştiricilerin kodlama sorumluluğunu test uzmanlarına aktarmak

d) Kalite tartışmalarını ekibin geliştirme kararlarından ayırmak

</div>



**Soru 19** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

What is the stated purpose of giving different test levels distinct test objectives?

a) To make defect correction unnecessary after the first test level has finished

b) To reduce unnecessary repetition of testing work between the test levels

c) To assign each test technique to a different level regardless of the test purpose

d) To replace work-product reviews with test execution at the later test levels

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Farklı test seviyelerine ayrı test hedefleri verilmesinin belirtilen amacı nedir?

a) İlk test seviyesi bittiğinde sonraki hata düzeltmelerine gerek kalmaması

b) Test seviyeleri arasındaki gereksiz test tekrarlarının azaltılması

c) Her test tekniğinin, hedefinden bağımsız olarak başka bir seviyeye atanması

d) İş ürünü gözden geçirmelerinin yerini sonraki seviyelerdeki test koşumunun alması

</div>



**Soru 20** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

An import service handles file extensions as follows: 'csv', 'json' and 'xml' each select a different supported reader; an empty extension returns MISSING; any other extension returns UNSUPPORTED. Each test supplies one extension. Four tests use the extensions 'csv', 'json', 'json' and an empty string. What equivalence partition coverage do these tests achieve across all the specified behaviors?

a) 40%

b) 80%

c) 60%

d) 100%

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir içe aktarma servisi `csv`, `json` ve `xml` uzantıları için üç farklı desteklenen okuyucu seçer; boş uzantıda MISSING, bunların dışındaki bir uzantıda UNSUPPORTED döndürür. Her test tek uzantı verir. Dört testin girdileri `csv`, `json`, `json` ve boş metindir. Geçerli ve geçersiz paylar birlikte sayıldığında, denklik paylarına ayırma (equivalence partitioning) kapsamında bu testler yüzde kaç kapsam sağlar?

a) %40

b) %80

c) %60

d) %100

</div>


### S21–S30



**Soru 21** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Which outcome is a stated benefit of obtaining frequent feedback from stakeholders during development?

a) The stakeholders take over the team's responsibility for test execution

b) The agreed scope stops changing after the first feedback discussion

c) The team can substitute informal comments for its acceptance criteria

d) The team can focus its effort on features that provide value to users

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Geliştirme sırasında paydaşlardan sık geri bildirim alınmasının belirtilen faydalarından biri hangisidir?

a) Paydaşların test koşumu sorumluluğunu ekipten devralması

b) İlk geri bildirim görüşmesinden sonra kararlaştırılan kapsamın değişmemesi

c) Ekibin kabul kriterleri yerine gayriresmî yorumları kullanabilmesi

d) Ekibin çabasını kullanıcıya değer sağlayan özelliklere yöneltebilmesi

</div>



**Soru 22** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team reviews both short user stories and a large contractual specification. A lead insists that the generic review process requires exactly the same detailed tasks and effort for both. Which response correctly describes the generic process?

a) Select suitable tasks and formality for the work product and the review's purpose

b) Rename the activities for each product, but keep their detailed tasks identical

c) Adjust the scope, but require equal depth and effort for every activity in both reviews

d) Use a review process for the contract and leave the short stories without a process

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip hem kısa kullanıcı hikâyelerini hem de büyük bir sözleşme belirtimini gözden geçirir. Ekip lideri, genel gözden geçirme sürecinin her ikisinde de tam olarak aynı ayrıntılı görevleri ve eforu gerektirdiğini ileri sürer. Genel süreci doğru açıklayan yanıt hangisidir?

a) İş ürününe ve gözden geçirme amacına uygun görevleri ve resmiyet düzeyini seçin.

b) Her ürün için aktivitelere farklı adlar verin, fakat ayrıntılı görevleri aynı tutun.

c) Kapsamı uyarlayın, ancak iki gözden geçirmedeki her aktiviteye eşit derinlik ve efor ayırın.

d) Sözleşme için gözden geçirme süreci kullanın, kısa hikâyeleri süreç dışında bırakın.

</div>



**Soru 23** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

An organization is considering removing an optional connector from an operational system. Before authorizing the change, the test team is asked to perform impact analysis. What is the purpose of that analysis at this point?

a) To produce pass/fail results for the tests that would follow implementation

b) To estimate the number of remaining defects from the previous release's pass rate

c) To identify affected areas and inform the decision whether to proceed

d) To establish that components outside the connector can be excluded from future testing

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir kuruluş, çalışan bir sistemden isteğe bağlı bir bağlayıcıyı kaldırmayı düşünmektedir. Değişikliği onaylamadan önce test ekibinden etki analizi (impact analysis) istenir. Analizin bu aşamadaki amacı nedir?

a) Değişiklik uygulandıktan sonra koşulacak testlerin geçti/kaldı sonuçlarını üretmek

b) Önceki sürümün test geçme oranından üründe kalan hata sayısını tahmin etmek

c) Etkilenecek alanları belirleyip değişikliğe devam etme kararına girdi sağlamak

d) Bağlayıcı dışındaki bileşenlerin sonraki test kapsamından çıkarılmasını kesinleştirmek

</div>



**Soru 24** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A self-organizing agile team wants everyone to see the current state of testing at any moment, without waiting for a written document. Which means of communicating test status BEST fits this need?

a) A test completion report distributed at the end of each test level

b) A monthly e-mail summary sent to all stakeholders

c) Minutes of the weekly status meetings

d) Dashboards such as task boards or burn-down charts

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Kendi kendini organize eden çevik bir ekip, yazılı bir belgeyi beklemeden herkesin testin güncel durumunu her an görebilmesini ister. Hangi iletişim yöntemi bu ihtiyaca **EN İYİ** uyar?

a) Her test seviyesinin sonunda dağıtılan test tamamlama raporu

b) Bütün paydaşlara her ay gönderilen e-posta özeti

c) Haftalık durum toplantılarının tutanakları

d) Görev panosu veya burn-down tablosu içeren gösterge paneli

</div>



**Soru 25** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team uses requirements-based prioritization. At each step it chooses the currently executable test case covering the highest-priority requirement (1 is highest). Prerequisites must have passed. TC-P has passed and no other test case has run. Which test case should run next?

| Test case | Requirement priority | Prerequisite | Status |
|---|---|---|---|
| TC-P | 4 | None | Passed |
| TC-Q | 2 | None | Not run |
| TC-R | 1 | TC-P | Not run |
| TC-S | 1 | TC-T | Not run |
| TC-T | 3 | None | Not run |

a) TC-Q

b) TC-R

c) TC-S

d) TC-T

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip gereksinim bazlı önceliklendirme kullanır. Her adımda, ön koşulları geçmiş ve o anda koşulabilir testler arasından en yüksek öncelikli gereksinimi kapsayanı seçer; 1 en yüksek önceliktir. TC-P geçmiştir, başka test koşulmamıştır.

| Test senaryosu | Gereksinim önceliği | Ön koşul | Durum |
|---|---:|---|---|
| TC-P | 4 | Yok | Geçti |
| TC-Q | 2 | Yok | Koşulmadı |
| TC-R | 1 | TC-P | Koşulmadı |
| TC-S | 1 | TC-T | Koşulmadı |
| TC-T | 3 | Yok | Koşulmadı |

Sırada hangi test senaryosu koşulmalıdır?

a) TC-Q

b) TC-R

c) TC-S

d) TC-T

</div>



**Soru 26** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

An iteration retrospective identifies a useful improvement to test data preparation. The team agrees on an owner and a follow-up date, but proposes leaving the outcome undocumented because everyone attended the meeting. Which response BEST supports effective use of the retrospective?

a) Record the outcome, include it in completion reporting and follow up the action

b) Replace the outcome with the iteration's pass rate in the completion report

c) Ask the testers to keep the outcome within their own group until the release

d) Repeat the discussion at the end of the project before assigning any action

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir döngü sonunda geçmişe dönük öğeler (retrospectives) ele alınırken test verisi hazırlığını iyileştirecek bir adım belirlenir. Ekip sorumluyu ve takip tarihini kararlaştırır; fakat herkes toplantıda olduğu için sonucu yazmamayı önerir. Bu çalışmadan etkili biçimde yararlanmayı **EN İYİ** destekleyen yanıt hangisidir?

a) Sonucu kaydedin, tamamlama raporuna alın ve aksiyonu izleyin.

b) Tamamlama raporunda bu sonucun yerine döngünün test geçme oranını yazın.

c) Sonucu sürüm çıkana kadar test uzmanlarının kendi grubu içinde tutun.

d) Aksiyon atamadan önce proje sonunda konuyu yeniden tartışın.

</div>



**Soru 27** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

During component testing, a team uses a coverage tool and reports that their tests exercised 85% of the branches. Which value of white-box testing does this illustrate?

a) The thoroughness of testing can be measured objectively through code coverage

b) Coverage figures prove that the component meets its requirements

c) The measured coverage shows that the remaining 15% of branches contain no defects

d) High coverage figures show that testing is complete and the component is ready for release

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bileşen testi yapan bir ekip, kapsam aracından testlerinin dalların %85’ini çalıştırdığını öğrenir. Bu sonuç beyaz kutu testinin hangi değerini örnekler?

a) Kod kapsamı üzerinden testin kapsamlılığının nesnel olarak ölçülebilmesi

b) Kapsam oranının bileşenin gereksinimleri karşıladığını kanıtlaması

c) Kalan %15’lik dal kümesinde hata bulunmadığının ölçümle gösterilmesi

d) Yüksek kapsamın testin tamamlandığını ve bileşenin yayıma hazır olduğunu göstermesi

</div>



**Soru 28** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Budget reductions leave a project with less time for security testing. The team identifies a greater chance that an unauthorized-access problem will reach production. Which statement BEST explains the relationship between the risks described?

a) Both items stop being risks because neither adverse outcome has occurred yet

b) The budget change turns the unauthorized-access risk into a project risk

c) Project constraints can increase exposure to a product quality risk

d) Assessing the access problem removes the need to manage the budget problem

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bütçe kesintileri nedeniyle bir projede güvenlik testi için daha az zaman kalır. Ekip, yetkisiz erişim sorununun üretime ulaşma olasılığının arttığını belirler. Bu riskler arasındaki ilişkiyi **EN İYİ** açıklayan ifade hangisidir?

a) Olumsuz sonuçlar henüz gerçekleşmediğinden ikisi de risk olmaktan çıkar.

b) Bütçe değişikliği, yetkisiz erişim riskini proje riskine dönüştürür.

c) Proje kısıtları, bir ürün kalitesi riskine maruz kalmayı artırabilir.

d) Erişim sorununu değerlendirmek, bütçe sorununu yönetme ihtiyacını kaldırır.

</div>



**Soru 29** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A search requirement says that leading and trailing spaces are ignored, but spaces inside a query are significant. The catalog contains one item named 'harita'. In build 6.4, on Browser X 129.0 / OS Y 15.1, a tester records:

| Query, including the shown spaces | Actual result |
|---|---|
| `"harita"` | The harita item is returned |
| `" harita "` | No items are returned |
| `"h arita"` | No items are returned |

Which defect description is supported by this requirement and these observations?

a) Search returns the harita item for 'harita' but no items for ' harita '; both should return that item

b) Search fails for the query 'harita', so the item cannot be retrieved without surrounding spaces

c) The query parser is corrupting the database whenever a query contains any space character

d) Search returns no items for 'h arita', although internal spaces should be ignored like outer spaces

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Arama gereksinimine göre sorgunun başındaki ve sonundaki boşluklar yok sayılır; içindeki boşluklar anlamlıdır. Katalogda adı `harita` olan tek bir öğe vardır. Yapı (build) 6.4, Tarayıcı X 129.0 / İşletim Sistemi Y 15.1 ortamında şu sonuçlar kaydedilir:

| Sorgu (gösterilen boşluklarla) | Gerçekleşen sonuç |
|---|---|
| `"harita"` | harita öğesi döner |
| `" harita "` | Hiçbir öğe dönmez |
| `"h arita"` | Hiçbir öğe dönmez |

Hangi hata açıklaması gereksinim ve gözlemlerle desteklenmektedir?

a) `harita` öğeyi bulur, ` harita ` bulmaz; ikisi de aynı öğeyi döndürmelidir.

b) `harita` sorgusu başarısızdır; öğe çevresinde boşluk bulunmadan getirilememektedir.

c) Sorgu ayrıştırıcısı, boşluk içeren her sorguda veri tabanındaki kayıtları bozmaktadır.

d) `h arita` sonuç döndürmez; iç boşluklar da dış boşluklar gibi yok sayılmalıdır.

</div>



**Soru 30** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team starts testing a new application. A tester wants to design tests for likely programming mistakes, using general knowledge of why software fails. A lead rejects the idea because no failures have yet been observed in this application. Which response BEST explains the use of error guessing here?

a) Wait for a failure in this application so that the technique has a confirmed observation

b) Anticipated mistakes can guide tests without a prior failure in this particular application

c) Replace the predicted mistakes with branch counts to preserve an experience-based approach

d) Treat the predicted mistakes as confirmed product defects before running the tests

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Yeni bir uygulamanın testine başlayan ekipte bir test uzmanı, yazılımların neden arızalandığına ilişkin genel bilgisiyle olası programlama yanlışları için testler tasarlamak ister. Lider, bu uygulamada henüz arıza görülmediği için öneriyi reddeder. Burada hata tahminlemenin (error guessing) kullanılmasını **EN İYİ** açıklayan yanıt hangisidir?

a) Teknik için doğrulanmış gözlem oluşana kadar bu uygulamada arıza beklenmelidir.

b) Bu uygulamada arıza görülmeden de öngörülen yanlışlar testlere yön verebilir.

c) Tecrübeye dayalı kalmak için öngörülen yanlışlar yerine dal sayıları kullanılmalıdır.

d) Testler koşulmadan önce öngörülen yanlışlar doğrulanmış ürün hataları sayılmalıdır.

</div>


### S31–S40



**Soru 31** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A tester designs additional tests based on intuition and on knowledge of how similar applications have behaved, without referring to the specification or to the code structure. Which category of test techniques is being used?

a) Black-box (specification-based) test techniques

b) White-box (structure-based) test techniques

c) Experience-based test techniques

d) Risk-based test techniques

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir test uzmanı, belirtime veya kod yapısına başvurmadan sezgisine ve benzer uygulamaların davranışları hakkındaki bilgisine dayanarak ek testler tasarlar. Hangi test tekniği kategorisini kullanmaktadır?

a) Kara kutu (belirtim bazlı) test teknikleri

b) Beyaz kutu (yapı bazlı) test teknikleri

c) Tecrübeye dayalı test teknikleri

d) Risk bazlı test teknikleri

</div>



**Soru 32** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A requirement says that an account must lock after three invalid passwords. The application still allows a fourth attempt. An engineer changes the test's expected result to allow that fourth attempt, and the test now passes; the requirement and application have not changed. Which statement correctly distinguishes testing from debugging in this situation?

a) Testing should locate and remove the product defect; debugging should adjust the expected test result

b) Testing is complete when the edited test passes; debugging is unnecessary if the requirement is unchanged

c) Testing should accept the observed behavior as its expectation; debugging should document it as the requirement

d) Testing should compare the product with the agreed requirement; debugging should remove the cause of the incorrect behavior

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Gereksinime göre hesap, üç yanlış parola girişinden sonra kilitlenmelidir. Uygulama dördüncü denemeye de izin verir. Bir mühendis testin beklenen sonucunu dördüncü denemeyi kabul edecek biçimde değiştirince test geçer; gereksinim ve uygulama değişmemiştir. Bu durumda test ile hata ayıklamayı (debugging) doğru ayıran ifade hangisidir?

a) Test ürün hatasını bulup gidermeli; hata ayıklama testin beklenen sonucunu değiştirmelidir.

b) Düzenlenen test geçince test işi tamamlanır; gereksinim değişmediyse hata ayıklama gerekmez.

c) Test gözlenen davranışı beklenti kabul etmeli; hata ayıklama bunu gereksinim olarak kaydetmelidir.

d) Test ürünü gereksinimle karşılaştırmalı; hata ayıklama yanlış davranışın nedenini gidermelidir.

</div>



**Soru 33** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

After introducing DevOps, a team can inspect performance and reliability trends from checks in each delivery pipeline run. The team uses the trends to discuss changes in these quality characteristics. Which testing benefit is illustrated?

a) Assurance that the delivered functions satisfy every business requirement

b) Greater insight into non-functional aspects of the delivered software

c) Reduced maintenance effort for the checks as the product evolves

d) A quality verdict for untested changes based on earlier pipeline results

</div>

<div lang="tr" class="bilingual-tr">

**TR**

DevOps kullanmaya başlayan bir ekip, teslimat hattının her koşumunda performans verimliliği ve güvenilirlik eğilimlerini görür. Bu kalite özelliklerindeki değişimleri değerlendirmek için eğilimleri kullanır. Hangi test faydası örneklenmektedir?

a) Teslim edilen işlevlerin bütün iş gereksinimlerini karşıladığının güvencesi

b) Yazılımın fonksiyonel olmayan yönleri hakkında daha fazla bilgi edinme

c) Ürün geliştikçe kontrollerin bakımında gereken çabanın azalması

d) Önceki hat sonuçlarıyla sınanmamış değişikliklerin kalitesine karar verme

</div>



**Soru 34** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A project introduces requirement reviews and code reviews in addition to its existing dynamic test levels. Which statement BEST describes the value this adds?

a) The reviews find the same defects as dynamic testing, but document them better

b) Defects can be detected earlier and removed more cheaply, before test execution begins

c) The reviews make later dynamic testing unnecessary for the reviewed work products

d) The reviews speed up test execution, because reviewed code runs faster

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir proje, mevcut dinamik test seviyelerine ek olarak gereksinim ve kod gözden geçirmelerini başlatır. Bunun eklediği değeri **EN İYİ** açıklayan ifade hangisidir?

a) Gözden geçirmeler dinamik testle aynı hataları bulur, ancak daha iyi belgeler.

b) Hatalar test koşumu başlamadan bulunup daha düşük maliyetle giderilebilir.

c) Gözden geçirilen iş ürünlerinde sonraki dinamik testlere gerek kalmaz.

d) Gözden geçirilen kod daha hızlı çalışacağı için test koşumu hızlanır.

</div>



**Soru 35** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team reruns a branch test suite ten times. Some runs use different input values, but every run exercises exactly the branches covered by the first run. The code is unchanged. How does the repetition affect branch coverage?

a) Each distinct input adds another item to branch coverage

b) Each distinct path through those branches adds another item to branch coverage

c) The suite's coverage is replaced by the branches exercised by its final test

d) It stays at the original level because no additional branch is exercised

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip dal test grubunu on kez yeniden koşar. Bazı koşumlarda farklı girdiler kullanılır, fakat her koşum ilk koşumdaki dalların tam olarak aynısını çalıştırır. Kod değişmemiştir. Tekrarlar dal kapsama yüzdesini nasıl etkiler?

a) Her farklı girdi, dal kapsamına yeni bir kapsam öğesi ekler.

b) Bu dallardan geçen her farklı yol, dal kapsamına yeni bir öğe ekler.

c) Grubun kapsamı, son testin çalıştırdığı dallarla değiştirilir.

d) Yeni bir dal çalıştırılmadığı için kapsama yüzdesi değişmez.

</div>



**Soru 36** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team evaluates fault tolerance by designing tests from the error-recovery branches in a component's source code. What are the classifications of the test objective and the basis used to derive the tests, respectively?

a) Functional testing, then white-box testing

b) White-box testing, then non-functional testing

c) Non-functional testing, then black-box testing

d) Non-functional testing, then white-box testing

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip hata toleransını değerlendirmek için bir bileşenin kaynak kodundaki hata sonrası toparlanma dallarından testler türetir. Testin amacı ve testlerin türetildiği esas, sırasıyla nasıl sınıflandırılır?

a) Fonksiyonel test; beyaz kutu testi

b) Beyaz kutu testi; fonksiyonel olmayan test

c) Fonksiyonel olmayan test; kara kutu testi

d) Fonksiyonel olmayan test; beyaz kutu testi

</div>



**Soru 37** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

During collaborative refinement, a team agrees that a user story has clear business value, can be estimated and tested, and is small enough for an iteration. However, it is tightly coupled to another story and cannot be delivered separately. Which INVEST characteristic needs attention?

a) Valuable, because the story's result provides no benefit to a user

b) Estimable, because the team has not formed an effort estimate

c) Testable, because the team has no way to check the result

d) Independent, because the stories have a delivery dependency

</div>

<div lang="tr" class="bilingual-tr">

**TR**

İş birliğine dayalı olgunlaştırma sırasında ekip, bir kullanıcı hikâyesinin açık iş değeri taşıdığını, tahminlenebilir ve test edilebilir olduğunu ve bir döngüye sığacak kadar küçük olduğunu kararlaştırır. Ancak hikâye başka bir hikâyeye sıkı bağlıdır ve ayrı teslim edilememektedir. INVEST’in hangi özelliğine dikkat edilmelidir?

a) Değerli (Valuable); çünkü hikâyenin sonucu kullanıcıya fayda sağlamamaktadır.

b) Tahminlenebilir (Estimable); çünkü ekip hikâyenin eforunu tahminleyememektedir.

c) Test edilebilir (Testable); çünkü ekip sonucu kontrol etmenin yolunu bulamamaktadır.

d) Bağımsız (Independent); çünkü hikâyelerin teslimatı birbirine bağlıdır.

</div>



**Soru 38** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

During requirements reviews, a team uses a document tool to associate each comment with the relevant passage and collect the reviewers' findings. A colleague says it cannot support testing because people still judge the content. Which response is correct?

a) The tool belongs to test execution because running any software tool is dynamic testing

b) Human judgment prevents a document review from receiving meaningful tool support

c) Static testing can receive tool support while people make the judgments

d) Review comments become test management data regardless of the activity the tool supports

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip gereksinim gözden geçirmelerinde her yorumu ilgili metin parçasına bağlayan ve gözden geçiricilerin bulgularını toplayan bir belge aracı kullanır. Bir çalışma arkadaşı, içeriği insanlar değerlendirdiği için aracın testi destekleyemeyeceğini söyler. Doğru yanıt hangisidir?

a) Herhangi bir yazılım aracını çalıştırmak dinamik test olduğundan araç test koşumuna aittir.

b) İçeriği insanların değerlendirmesi, belge gözden geçirmesinde anlamlı araç desteğini engeller.

c) İçeriğe ilişkin yargıyı insanlar oluştururken statik test de araçlarla desteklenebilir.

d) Aracın desteklediği aktiviteye bakılmaksızın yorumlar test yönetimi verisi olarak sınıflandırılır.

</div>



**Soru 39** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

Two teams use the same lifecycle and have similar staffing. One tests a browser extension across browser configurations; the other tests sensor firmware using a hardware rig and simulated device interfaces. Which contextual factor most directly explains these different test environments?

a) The lifecycle requires different test environments even when it is the same for both teams

b) The technical characteristics of each test object affect the environment needed for testing

c) The staffing level determines which interfaces each product needs to expose

d) The test environment should be standardized across products regardless of their interfaces

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Aynı yaşam döngüsünü kullanan ve benzer sayıda çalışanı olan iki ekipten biri tarayıcı eklentisini farklı tarayıcı ayarlarında, diğeri sensör aygıt yazılımını donanım düzeneği ve benzetimli cihaz arayüzleriyle sınar. Test ortamlarının farklı olmasını en doğrudan hangi bağlam faktörü açıklar?

a) İki ekipte de aynı olan yaşam döngüsünün farklı test ortamlarını zorunlu kılması

b) Test nesnelerinin teknik özelliklerinin gerekli test ortamını etkilemesi

c) Ekiplerdeki çalışan sayısının ürünlerin sunacağı arayüzleri belirlemesi

d) Ürün arayüzlerinden bağımsız ortak bir test ortamının standartlaştırılması

</div>



**Soru 40** (1 puan)

<div lang="en" class="bilingual-en">

**EN**

A team adds new tests as its product evolves but also keeps a stable set of checks for existing behavior. A colleague says the principle 'tests wear out' means those stable checks should be discarded merely because they are repeated. Which response BEST interprets the principle?

a) The stable checks should replace the new tests because their past results are known

b) A check that passed before can be omitted when the same behavior is changed

c) Repeated checks can still help reveal regressions, while new tests address new defect opportunities

d) Repeated checks establish that the previously tested behavior remains free of defects

</div>

<div lang="tr" class="bilingual-tr">

**TR**

Bir ekip ürün geliştikçe yeni testler eklerken mevcut davranışlar için yerleşik bir test kümesini de korur. Bir çalışma arkadaşı, “testler yıpranır (tests wear out)” ilkesinin bu kontrollerin tekrarlandıkları için atılmasını gerektirdiğini söyler. İlkeyi **EN İYİ** yorumlayan yanıt hangisidir?

a) Geçmiş sonuçları bilinen mevcut kontroller yeni testlerin yerini almalıdır.

b) Daha önce geçen bir kontrol, sınadığı davranış değiştiğinde atlanabilir.

c) Tekrarlar regresyonları bulabilir; yeni testler farklı hataları arar.

d) Tekrarlanan kontroller, sınanan mevcut davranışların hatasız kaldığını kanıtlar.

</div>


## Part 2 — Cevap anahtarı ve skor değerlendirmesi

### Cevap anahtarı

| Soru | Cevap | Bölüm | LO | K |
|---|---|---|---|---|
| 1 | b | 4 | FL-4.2.3 | K3 |
| 2 | a | 1 | FL-1.4.1 | K2 |
| 3 | d | 6 | FL-6.2.1 | K1 |
| 4 | d | 4 | FL-4.2.4 | K3 |
| 5 | b | 5 | FL-5.4.1 | K2 |
| 6 | c | 3 | FL-3.2.5 | K1 |
| 7 | a | 5 | FL-5.2.1 | K1 |
| 8 | a | 2 | FL-2.1.3 | K1 |
| 9 | b | 5 | FL-5.1.4 | K3 |
| 10 | a | 5 | FL-5.1.7 | K2 |
| 11 | c | 5 | FL-5.1.1 | K2 |
| 12 | c | 4 | FL-4.2.2 | K3 |
| 13 | d | 1 | FL-1.4.5 | K2 |
| 14 | b | 4 | FL-4.5.3 | K3 |
| 15 | c | 1 | FL-1.5.1 | K2 |
| 16 | c | 4 | FL-4.4.2 | K2 |
| 17 | b | 1 | FL-1.2.2 | K1 |
| 18 | a | 1 | FL-1.5.2 | K1 |
| 19 | b | 2 | FL-2.1.2 | K1 |
| 20 | c | 4 | FL-4.2.1 | K3 |
| 21 | d | 3 | FL-3.2.1 | K1 |
| 22 | a | 3 | FL-3.2.2 | K2 |
| 23 | c | 2 | FL-2.3.1 | K2 |
| 24 | d | 5 | FL-5.3.3 | K2 |
| 25 | b | 5 | FL-5.1.5 | K3 |
| 26 | a | 2 | FL-2.1.6 | K2 |
| 27 | a | 4 | FL-4.3.3 | K2 |
| 28 | c | 5 | FL-5.2.2 | K2 |
| 29 | a | 5 | FL-5.5.1 | K3 |
| 30 | b | 4 | FL-4.4.1 | K2 |
| 31 | c | 4 | FL-4.1.1 | K2 |
| 32 | d | 1 | FL-1.1.2 | K2 |
| 33 | b | 2 | FL-2.1.4 | K2 |
| 34 | b | 3 | FL-3.1.2 | K2 |
| 35 | d | 4 | FL-4.3.2 | K2 |
| 36 | d | 2 | FL-2.2.2 | K2 |
| 37 | d | 4 | FL-4.5.1 | K2 |
| 38 | c | 6 | FL-6.1.1 | K2 |
| 39 | b | 1 | FL-1.4.2 | K2 |
| 40 | c | 1 | FL-1.3.1 | K2 |

### Skor bantları

- **35–40:** Bu denemede güçlü bir sonuç aldınız; başka bir süreli denemeyle doğrulayın.
- **30–34:** Bu denemede geçme çizgisinin üzerindesiniz; yanlışlarınızı gözden geçirin.
- **26–29:** Geçer; zayıf bölümlerinizi güçlendirin.
- **0–25:** Bu denemede geçme çizgisinin altındasınız; bölüm skor kartına göre çalışma rotası belirleyin.

Bu bantlar ilk, cevaplara bakılmadan yapılan süreli deneme için çalışma önerisidir; tekrar çözüm aynı ölçüm değildir; tek bir deneme sonucu gerçek sınav başarısını garanti etmez. Çalışma modunda açıklamaları görerek alınan puanı süreli prova puanıyla karşılaştırmayın.

### Bölüm skor kartı

Hedef, her bölümde en az %65 için gereken doğru sayısıdır; kesirli sonuç yukarı yuvarlanır. Bu bölüm hedefleri resmî bölüm bazında geçme barajı değildir. Resmî geçme ölçütü toplam 26/40'tır.

| Bölüm | Soru sayısı | Doğru sayınız | Hedef (%65) | Çalışma önerisi |
|---|---:|---|---|---|
| 1 — Temeller | 8 | | 6/8 | Hedefleri, aktiviteleri ve temel kavram ayrımlarını tekrar edin. |
| 2 — Yaşam döngüsü | 6 | | 4/6 | Test seviyelerini, önce test ve sola alma yaklaşımlarını karşılaştırın. |
| 3 — Statik test | 4 | | 3/4 | Statik/dinamik ayrımı, roller ve gözden geçirme türlerini çalışın. |
| 4 — Analiz ve tasarım | 11 | | 8/11 | Teknikleri veri üzerinde uygulayın, yanlış varyantları karşılaştırın. |
| 5 — Yönetim | 9 | | 6/9 | Planlama, tahmin, önceliklendirme, raporlama ve hata yönetimini çalışın. |
| 6 — Araçlar | 2 | | 2/2 | Araç işlevlerini ve otomasyon risklerini tekrar edin. |


## Part 3 — Açıklamalar

### S1–S10

**Soru 1 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Standart müşteride kupon değeri önemsizdir; birinci ve üçüncü test R1’i kapsar. 2. İkinci ve dördüncü test R2’yi kapsar. Böylece kapsanan küme {R1,R2} olur. 3. Eksik kurallar R3, R4 ve R5’tir. Bir girdi tek sütunu çalıştırdığı için her biri için birer test, toplam 3 ek test gerekir.

**En cazip yanlış (near-miss) — a:** Beş kuraldan dört koşumu çıkarmak 1 sonucunu verir. Ancak dört koşum dört farklı kuralı değil, iki kuralı tekrar tekrar çalıştırmıştır.

**Diğer şıklar:** c) 2 sonucu üç eksik kuraldan birini dışarıda bırakır veya tek girdinin iki müşteri seviyesini çalıştırabildiğini varsayar. · d) 5 sonucu mevcut R1 ve R2 kapsamını yok sayar. Soru tüm testleri yeniden kurmayı değil, eklenecek en az sayıyı sorar.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.3 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-3)

**Soru 2 — Doğru cevap: a**

**Neden doğru:** Tamamlanan testlerden kalan ürünlerin arşivlenmesi, yararlı testlerin başka ekiplere devri ve çıkarılan derslerin değerlendirilmesi test tamamlama (test completion) kapsamındadır. Kök bu kapanış işlerini birlikte verir.

**En cazip yanlış (near-miss) — b:** İlerlemeyi değerlendirmek de analiz içerdiği için bu seçenek caziptir. Ancak test gözetimi ve kontrolü, sürmekte olan işi planla karşılaştırır ve gerektiğinde yönlendirir; burada kapanış yapılmaktadır.

**Diğer şıklar:** c) Test uyarlama (test implementation), koşum için test çalışma ürünlerini hazırlamaya odaklanır. Arşivleme ve devir bu hazırlık değildir. · d) Planlama hedefleri ve yaklaşımı belirler. Buradaki işler biten test çalışmasının kapanışına aittir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.1 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-1)

**Soru 3 — Doğru cevap: d**

**Neden doğru:** Otomasyon aynı kontrolleri tutarlı biçimde tekrarlayabilir ve sonuçların daha nesnel karşılaştırılmasını destekleyebilir. Bu potansiyel bir faydadır; testlerin neyi ve nasıl kontrol ettiğine bağlıdır. Tasarım kalitesi ve bakım gereksinimi önemini korur.

**En cazip yanlış (near-miss) — c:** Otomatik kontrolün tutarlılığı, sonucun tasarımdan bağımsız biçimde güvenilir olduğu izlenimini verebilir. Ancak yanlış davranışı kontrol eden bir test tutarlı çalışsa da iyi bir sonuç sağlamaz.

**Diğer şıklar:** a) Otomatik kontroller uygulanmış kapsamı değerlendirir; temsil edilmeyen iş ihtiyaçlarının kapsandığını göstermez. · b) Ürün değişikliği otomatik test çalışma ürünlerinde güncelleme gerektirebilir; bakım eforu ortadan kalkmaz.

*Kaçırdıysanız tekrar edin: Test otomasyonunun faydaları ve riskleri | Tuzak: Kaynak bilgi eksiği | LO: FL-6.2.1 (K1)*

[Kılavuzda tekrar edin: Test otomasyonunun faydaları ve riskleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-2-1)

**Soru 4 — Doğru cevap: d**

**Neden doğru:** Adım adım: 1. Yeni durumunda öde olayı Ödendi’ye götürür. 2. Gönder olayı Gönderildi’ye götürür. 3. Gönderildi’den iptal et geçişi tanımlı değildir. Bu nedenle d dizisinin önceki adımları geçerliyken son adımı geçersizdir.

**En cazip yanlış (near-miss) — b:** İptal et olayı arandığı için bu dizi caziptir. Ancak Ödendi’den iptal etmeye izin verilir; dizinin iki adımı da geçerlidir.

**Diğer şıklar:** a) Yeni → Ödendi → Gönderildi → Teslim edildi geçişlerinin tamamı tanımlıdır. · c) Yeni’den iptal etmeye izin verilir; tek adımlı dizi geçerlidir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.4 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-4)

**Soru 5 — Doğru cevap: b**

**Neden doğru:** Onaylanmış temel çizgi değişiklik kontrolü altında tutulur. Değişikliğin izlenmesi ve ortaya çıkan yapılandırmanın ayrı tanımlanması, her sonucun kullanılan ortamla ilişkilendirilmesini sağlar.

**En cazip yanlış (near-miss) — a:** İnceleme notları iz bırakıyor gibi görünebilir. Ancak ortak ayarı kontrolsüz değiştirmek, temel çizgiye ilişkin değişiklik kontrolünü ve güvenilir sürüm kimliğini karşılamaz.

**Diğer şıklar:** c) Aynı kimlik altında farklı ayarlar kullanmak, hangi sonuçta hangi ortamın bulunduğunu belirsizleştirir. · d) Önceki yapılandırmanın kaydı, geçmiş sonuçların yeniden kurulması ve izlenmesi için gerekli olabilir. Yeni sonuç alınması bu ihtiyacı ortadan kaldırmaz.

*Kaçırdıysanız tekrar edin: Yapılandırma yönetimi | Tuzak: Kaynak bilgi eksiği | LO: FL-5.4.1 (K2)*

[Kılavuzda tekrar edin: Yapılandırma yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-4-1)

**Soru 6 — Doğru cevap: c**

**Neden doğru:** Gözden geçirmeye katılanların rollerine uygun eğitim alması başarı faktörlerinden biridir. Rollerin gerektirdiği görevleri öğrenmek, bu görevlerin doğru biçimde yerine getirilmesini destekler.

**En cazip yanlış (near-miss) — d:** Daha resmî bir süreç görevleri belirginleştirebilir. Ancak görev tanımının bulunması, o rolü yerine getirmek için gereken hazırlık ve eğitimin yerine geçmez.

**Diğer şıklar:** a) Daha büyük bir bölüm vermek rol bilgisini sağlamaz; hazırlıksız katılımcının yükünü artırabilir. · b) Gözden geçirmenin amacı iş ürününü değerlendirmektir. Bulguları bireysel performans ölçümüne dönüştürmek başarıyı destekleyen eğitim önlemi değildir.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.5 (K1)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-5)

**Soru 7 — Doğru cevap: a**

**Neden doğru:** Risk seviyesi olasılık ve etkiyle ilişkilidir. Etki aynı kalırken olasılığın artması seviyeyi yükseltir. Bu soru sayısal hesap değil, faktörlerin yönünü tanımayı gerektirir.

**En cazip yanlış (near-miss) — c:** Etki de risk seviyesini belirlediği için dikkat çekebilir. Ancak seçenekte etki artmamakta, azalmaktadır; bu risk seviyesini yükselten yön değildir.

**Diğer şıklar:** b) Etki aynıyken olasılığı azaltmak risk seviyesini artırmaz. · d) İki faktör de aynı kalırsa bu faktörlerden kaynaklanan bir artış olmaz.

*Kaçırdıysanız tekrar edin: Risk yönetimi | Tuzak: Kaynak bilgi eksiği | LO: FL-5.2.1 (K1)*

[Kılavuzda tekrar edin: Risk yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-2-1)

**Soru 8 — Doğru cevap: a**

**Neden doğru:** TDD küçük bir davranışı sınayan çalıştırılabilir testle başlar. Bu testi geçirecek kod geliştirilir; ardından testler geçmeye devam ederken yapı iyileştirilebilir. Sonraki küçük kod değişikliğini yönlendiren iş ürünü testtir.

**En cazip yanlış (near-miss) — b:** İş temsilcileriyle ortak senaryolar oluşturmak da geliştirmeden önce yapılabilir. Ancak anlatı biçimindeki ortak iş senaryosu, sorulan küçük davranış biriminin çalıştırılabilir TDD testi değildir.

**Diğer şıklar:** c) Hata raporu gözlenen bir anomaliyi kaydeder. TDD başlamak için yayımlanan üründe arıza bulunmasını gerektirmez. · d) Koşum kaydı tamamlanmış çalışmanın sonucudur; sonraki küçük kod değişikliğini başlatan test değildir.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.3 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-3)

**Soru 9 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Üç noktalı ağırlıklı tahmin E = (a + 4m + b) / 6’dır. 2. İçe aktarma için (3 + 4×7 + 17)/6 = 48/6 = 8 kişi-saat. 3. Bildirim için (5 + 4×9 + 25)/6 = 66/6 = 11 kişi-saat. 4. Toplam efor 8 + 11 = 19 kişi-saat; ayrılan 20 kişi-saatten 1 kişi-saat kalır. Efor toplanır; paralel çalışma toplam iş miktarını ortadan kaldırmaz.

**En cazip yanlış (near-miss) — a:** Üç değerin basit aritmetik ortalaması görevler için 9 ve 13, toplamda 22 verir. Caziptir çünkü üç tahmini de kullanır. Ancak ders programındaki üç noktalı tahminleme en olası değere dört kat ağırlık verir.

**Diğer şıklar:** c) 16, yalnız en olası değerleri 7 + 9 biçiminde toplayıp iyimser ve kötümser tahminleri dışarıda bırakır. · d) 11, iki tahminin büyüğünü alır. Bu, paralel işte geçen süreyi toplam eforla karıştırır; soru kişi-saat toplamını ister.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.4 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-4)

**Soru 10 — Doğru cevap: a**

**Neden doğru:** Test çeyrekleri teknolojiye veya işe dönük olmayı ve ekibi destekleme veya ürünü eleştirme amacını birlikte ele alır. Otomasyon bu iki eksenin yerine geçmez. Bu nedenle otomatik olmaları iki kontrolü aynı çeyreğe yerleştirmeyi gerektirmez.

**En cazip yanlış (near-miss) — b:** Otomasyon teknik araçlarla uygulandığı için caziptir. Ancak çeyrekler araç veya programlama dili sınıflandırması değildir.

**Diğer şıklar:** c) Çeyrekler testlerin kodlamadan önce veya sonra yazılmasına göre tanımlanmaz; geliştirmeden önce hazırlanmış testler de olabilir. · d) Çeyrekleri testleri koşan kişilere göre ayırmak bakış açısı ve amaç eksenlerini karşılamaz.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.7 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-7)


### S11–S20

**Soru 11 — Doğru cevap: c**

**Neden doğru:** İletişim düzeni, kime hangi biçimde ve ne sıklıkla bilgi verileceğini belirler. Bu bilgilerin test planına eklenmesi paydaşların ilerleme bilgisini nasıl alacağı konusundaki boşluğu doğrudan kapatır.

**En cazip yanlış (near-miss) — a:** Koşum kayıtları ilerleme bilgisi içerdiği için caziptir. Ancak ham sonuçlar kime, nasıl ve ne zaman bildirim yapılacağını belirlemez.

**Diğer şıklar:** b) Koşum komutları teknik uygulama ayrıntısıdır; paydaş iletişimi düzenini tanımlamaz. · d) Anomali incelemeleri ayrı iş ürünleridir. Tamamlanmış sonuçları toplamak durum bildirimlerinin düzenini belirlemez.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Near-miss karışıklığı | LO: FL-5.1.1 (K2)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-1)

**Soru 12 — Doğru cevap: c**

**Neden doğru:** Adım adım: 1. Paylar x ≤ 36, x = 37 ve x ≥ 38’dir. Sonlu sınır değerleri 36, 37 ve 38 olur. 2. Her sınırın iki komşusuyla kümeleri {35,36,37}, {36,37,38} ve {37,38,39} bulunur. 3. Birleşim {35,36,37,38,39} olduğundan 5 farklı girdi gerekir. Tek değerli orta pay yüzünden kümeler örtüşür.

**En cazip yanlış (near-miss) — d:** Geniş bir orta aralık ve iki yan pay için kullanılan sekiz değerli örüntü hatırlanabilir. Burada orta pay tek değerdir; komşuluklar örtüştüğü için aynı sayı kullanılamaz.

**Diğer şıklar:** a) 3 sonucu, yalnız merkez çevresindeki değerleri alıp 36’nın alt ve 38’in üst komşusunu dışarıda bırakır. · b) 9 sonucu, üç sınır için üçer değeri toplarken tekrarlanan değerleri yeniden sayar. Soru farklı girdileri istemektedir.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.2 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-2)

**Soru 13 — Doğru cevap: d**

**Neden doğru:** Test yönetimi rolü genel test sürecinin planlanması, gözetimi ve kontrolüne odaklanır. Paydaşlarla kapsamı ve kaynakları yeniden kararlaştırmak bu sorumluluğa girer. Diğer görevler testin teknik analizi veya hazırlanmasıyla ilgilidir.

**En cazip yanlış (near-miss) — a:** Risklere göre öncelik vermek yönetim işi gibi görünebilir. Ancak burada sıralanan öğeler test koşullarıdır; bu görev test analizinin ve test rolünün parçasıdır.

**Diğer şıklar:** b) Test esasının test edilebilirliğini değerlendirmek test analizine aittir. · c) Hazırlanan ortamı gereksinimlerine göre doğrulamak test koşumuna hazırlıktır; genel kapsam ve kaynak dağılımı kararı değildir.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Kaynak bilgi eksiği | LO: FL-1.4.5 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-5)

**Soru 14 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Kriterde geçerli kodun %15 indirim oluşturması istenir. 2. Tek bir reddedilen-kod durumu için hem hata mesajı hem tam fiyat istenir. 3. b kümesi bu olumlu ve olumsuz durumu, belirtilen çıktılarıyla birlikte kapsar. Kökte geçersiz ve süresi dolmuş kod aynı durum olarak tanımlandığından ikisinin ayrı temsil edilmesi şart değildir.

**En cazip yanlış (near-miss) — c:** İki farklı reddedilen kodu sınadığı için kapsamlı görünebilir. Ancak olumlu senaryoyu ve tam fiyat koşulunu atlar; aynı olumsuz durumun iki örneğini çoğaltır.

**Diğer şıklar:** a) Olumlu senaryoyu sınar, fakat reddedilen kodun hata mesajı ve tam fiyat davranışını kapsamaz. · d) Geçerli kodu tekrar sınar ve kriterde bulunmayan saklama ayrıntısını ekler. Reddedilen kodun davranışı açık kalır.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Prosedür hatası | LO: FL-4.5.3 (K3)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-3)

**Soru 15 — Doğru cevap: c**

**Neden doğru:** Araç yapılandırma, kayıtları yorumlama ve veri tabanı sorgulama teknik bilgi gerektirir. Kök, iş kuralını belirlemek veya sonucu sunmak yerine bu teknik çalışmaları anlatır.

**En cazip yanlış (near-miss) — a:** Beklenen davranışı bilmek için alan bilgisi yararlıdır. Ancak belirtilen araç ve arayüzlerle çalışmayı en doğrudan açıklayan beceri teknik bilgidir.

**Diğer şıklar:** b) İletişim becerisi bulguları anlatmayı destekler; kökteki teknik işlemleri gerçekleştirme becerisiyle aynı değildir. · d) Ekip çalışması sorumluluğu paylaşmayı destekler; araç kullanımı ve sorgu yazmanın teknik gereğini karşılamaz.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Near-miss karışıklığı | LO: FL-1.5.1 (K2)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-1)

**Soru 16 — Doğru cevap: c**

**Neden doğru:** Oturum formu izlenen adımların ve keşfedilen bulguların kaydedilmesini ve sonradan görüşülmesini destekler. Keşif sırasında not almak; öğrenme, test tasarımı, koşum ve değerlendirme arasındaki ilişkiyi ortadan kaldırmaz.

**En cazip yanlış (near-miss) — a:** Yazılı adımlar önceden hazırlanmış testleri çağrıştırabilir. Ancak burada yapılanların kaydı tutulur; daha önce bütün adımları sabitlemekten söz edilmez.

**Diğer şıklar:** b) Sonuçlar keşif sırasında da değerlendirilir. Sonraki görüşme bu değerlendirme ihtiyacını kaldırmaz. · d) Kayıt tutmak tam kapsamın kanıtı değildir. Oturumun kapsamadığı alanlar bulunabilir.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.4.2 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-2)

**Soru 17 — Doğru cevap: b**

**Neden doğru:** Test bulguları, geliştirme ve test süreçlerinde nelerin iyileştirilebileceğini gösterebilir. Kalite güvencesi bu bilgiyi süreçleri geliştirmek ve benzer hataları önlemek için kullanır. Test ürün hakkında kanıt sağlar; kalite güvencesinin odağı süreçtir.

**En cazip yanlış (near-miss) — c:** Geçme oranı testten gelen bir bilgi olduğu için caziptir. Ancak ürünün test sonucu, onu üreten sürecin değerlendirilmesinin yerini tutmaz.

**Diğer şıklar:** a) Bir hatayı bildirmek, onu düzeltme sorumluluğunu test ekibine devretmez. Hata ayıklama bir geliştirme aktivitesidir. · d) Sınanan kapsamdan, gelecekteki bütün ihtiyaçların karşılandığı sonucu çıkarılamaz.

*Kaçırdıysanız tekrar edin: Test neden gereklidir? | Tuzak: Near-miss karışıklığı | LO: FL-1.2.2 (K1)*

[Kılavuzda tekrar edin: Test neden gereklidir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-2-2)

**Soru 18 — Doğru cevap: a**

**Neden doğru:** Test uzmanları yakın iş birliğiyle test bilgisini ekip arkadaşlarına aktarabilir ve geliştirme kararlarına katkıda bulunabilir. Bu katkı, diğer üyelerin becerilerini tamamlar; görev ve yetkilerinin devri anlamına gelmez.

**En cazip yanlış (near-miss) — b:** İş temsilcileriyle kabul testlerini konuşmak, iş önceliklerini onaylamakla karıştırılabilir. Görüşmelere katılmak ürün sahibinin karar yetkisini vermez.

**Diğer şıklar:** c) Bilgi paylaşımı geliştiricilerin test edilebilirliği düşünmesine yardımcı olur; kodlama görevlerini test uzmanlarına taşımaz. · d) Kalite konularını geliştirme kararlarından ayırmak, yaklaşımın iş birliği amacına ters düşer.

*Kaçırdıysanız tekrar edin: Testte temel beceriler ve iyi uygulamalar | Tuzak: Near-miss karışıklığı | LO: FL-1.5.2 (K1)*

[Kılavuzda tekrar edin: Testte temel beceriler ve iyi uygulamalar](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-5-2)

**Soru 19 — Doğru cevap: b**

**Neden doğru:** Seviyelerin farklı hedefleri olması, her seviyenin farklı bilgi sağlamasını ve gereksiz iş tekrarının azaltılmasını destekler. Bu iyi uygulama teknikleri seviyelere özel kılmaz ve sonraki hata düzeltmelerini ortadan kaldırmaz.

**En cazip yanlış (near-miss) — c:** Farklı hedefler farklı teknikleri düşündürebilir. Ancak bir teknik, amaca bağlı olarak birden fazla seviyede kullanılabilir; her tekniğe ayrı seviye ayrılmaz.

**Diğer şıklar:** a) İlk seviyeden sonra da düzeltilmesi gereken hatalar bulunabilir. · d) Gözden geçirme ile dinamik test farklı bilgi sağlar; seviye hedeflerinin ayrılması birini diğerinin yerine koymaz.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Kaynak bilgi eksiği | LO: FL-2.1.2 (K1)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-2)

**Soru 20 — Doğru cevap: c**

**Neden doğru:** Adım adım: 1. Beş ayrı davranış beş pay verir: csv, json, xml, boş ve diğer uzantılar. 2. Testler csv, json ve boş paylarını çalıştırır. İkinci json girdisi aynı payın tekrarıdır. 3. Kapsanan farklı pay sayısı 3’tür; kapsam 3/5 × 100 = %60 olur. Boş ve diğer uzantılar reddedilse de kapsam hesabına katılır.

**En cazip yanlış (near-miss) — b:** Dört test koşulduğu için 4/5 = %80 sonucu caziptir. Ancak kapsam öğesi test sayısı değil, çalıştırılan farklı denklik paylarıdır; json iki kez sayılmaz.

**Diğer şıklar:** a) %40, boş uzantı payını atlayıp yalnız iki desteklenen okuyucuyu sayma hatasıdır. Geçersiz pay da kapsam öğesidir. · d) Testlerin geçmesi %100 denklik payı kapsamı sağlamaz. Xml ve diğer uzantı payları henüz çalıştırılmamıştır.

*Kaçırdıysanız tekrar edin: Kara kutu test teknikleri | Tuzak: Prosedür hatası | LO: FL-4.2.1 (K3)*

[Kılavuzda tekrar edin: Kara kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-2-1)


### S21–S30

**Soru 21 — Doğru cevap: d**

**Neden doğru:** Erken ve sık geri bildirim, ekibin kullanıcıya değer sağlayan özelliklere odaklanmasına yardımcı olur. Paydaşların ihtiyaçları öğrenildikçe efor daha yararlı işlere yönlendirilebilir.

**En cazip yanlış (near-miss) — c:** Gayriresmî yorumlar da değerli geri bildirim olabilir. Ancak bu, kabul kriterlerinin yerine yorum koymak anlamına gelmez; geri bildirim kriterlerin netleşmesine yardımcı olabilir.

**Diğer şıklar:** a) Geri bildirim sağlamak test koşumu sorumluluğunu devralmak değildir. · b) İhtiyaçların anlaşılması kapsamın güncellenmesini gerektirebilir. İlk görüşme kapsamı sabitlemez.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Kaynak bilgi eksiği | LO: FL-3.2.1 (K1)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-1)

**Soru 22 — Doğru cevap: a**

**Neden doğru:** Genel gözden geçirme süreci ortak bir çerçeve sunar; ayrıntıları iş ürününe, amaca ve bağlama göre uyarlanabilir. Kısa bir hikâye ile kapsamlı sözleşmenin aynı görev ayrıntısı ve efor gerektirmesi beklenmez.

**En cazip yanlış (near-miss) — c:** Kapsamı uyarlaması doğru bir başlangıçtır. Fakat her aktivitede aynı derinlik ve eforu zorunlu tutarak bağlama uyarlamayı yeniden sınırlar.

**Diğer şıklar:** b) Aktivite adlarını değiştirmek, görevleri bağlama uygun hâle getirmek değildir. · d) Kısa hikâyelerin de uygun bir gözden geçirme süreci olabilir; boyutları onları süreç dışında bırakmayı gerektirmez.

*Kaçırdıysanız tekrar edin: Geri bildirim ve gözden geçirme süreci | Tuzak: Near-miss karışıklığı | LO: FL-3.2.2 (K2)*

[Kılavuzda tekrar edin: Geri bildirim ve gözden geçirme süreci](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-2-2)

**Soru 23 — Doğru cevap: c**

**Neden doğru:** Bakım değişikliğinden önce etki analizi, etkilenecek alanları ve olası sonuçları anlamaya yardım eder. Bu bilgi değişikliğin yapılıp yapılmayacağı kararını destekleyebilir. Kökte karar öncesi aşama sorulmaktadır.

**En cazip yanlış (near-miss) — a:** Değişiklikten sonra test gerekeceği için makul görünebilir. Ancak henüz uygulanmamış değişikliğin test sonuçları bu analizle üretilemez.

**Diğer şıklar:** b) Geçme oranı, üründeki kalan hata sayısını bu biçimde belirlemez ve istenen değişiklik etki analizi değildir. · d) Analiz diğer bileşenlerde de etki gösterebilir. Bağlayıcı dışındaki alanların peşinen kapsamdan çıkarılmasını sağlamaz.

*Kaçırdıysanız tekrar edin: Bakım testi | Tuzak: Near-miss karışıklığı | LO: FL-2.3.1 (K2)*

[Kılavuzda tekrar edin: Bakım testi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-3-1)

**Soru 24 — Doğru cevap: d**

**Neden doğru:** Güncel tutulan gösterge panelleri (dashboards), görev panoları ve burn-down tabloları testin durumunu görünür kılar. Kök, belirli bir rapor tarihini beklemeden anlık erişim istemektedir.

**En cazip yanlış (near-miss) — b:** E-posta bütün paydaşlara ulaşabildiği için uygun görünebilir. Ancak aylık bildirim, güncel durumu her an görme ihtiyacını karşılamaz.

**Diğer şıklar:** a) Tamamlama raporu biten bir seviyeyi özetler; seviyenin sonunu bekletir. · c) Haftalık tutanaklar toplantı anının kaydıdır. Sürekli güncel görünürlük için tek başlarına yeterli değildir.

*Kaçırdıysanız tekrar edin: Test gözetimi, kontrolü ve tamamlama | Tuzak: Near-miss karışıklığı | LO: FL-5.3.3 (K2)*

[Kılavuzda tekrar edin: Test gözetimi, kontrolü ve tamamlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-3-3)

**Soru 25 — Doğru cevap: b**

**Neden doğru:** Adım adım: 1. Geçmiş olan TC-P’yi adaylardan çıkarın. 2. Ön koşulu TC-T geçmediği için TC-S’yi eleyin. 3. Hazır küme TC-Q, TC-R ve TC-T’dir; öncelikleri sırasıyla 2, 1 ve 3’tür. 4. Hazır testlerin en yüksek önceliklisi TC-R’dir. Hazır kümede eşit öncelik yoktur.

**En cazip yanlış (near-miss) — c:** TC-S de 1 önceliğine sahiptir. Ancak ön koşulu henüz sağlanmamıştır; yüksek önceliği onu koşulabilir yapmaz.

**Diğer şıklar:** a) TC-Q hazırdır fakat 2 önceliklidir. Hazır olan TC-R’nin 1 önceliği daha yüksektir. · d) TC-T daha sonra TC-S’yi açabilir. Ancak verilen kural, hazır testleri kendi gereksinim öncelikleriyle karşılaştırır; TC-R şimdi daha önceliklidir.

*Kaçırdıysanız tekrar edin: Test planlama | Tuzak: Prosedür hatası | LO: FL-5.1.5 (K3)*

[Kılavuzda tekrar edin: Test planlama](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-1-5)

**Soru 26 — Doğru cevap: a**

**Neden doğru:** Belirlenen iyileştirme kaydedilmeli, test tamamlama raporlamasına yansıtılmalı ve uygulaması izlenmelidir. Toplantıya katılmak kararın daha sonra hatırlanmasını veya uygulanmasını güvence altına almaz.

**En cazip yanlış (near-miss) — b:** Geçme oranı somut bir ölçüt olduğu için rapora uygun görünebilir. Ancak iyileştirme kararını ve aksiyon takibini karşılamaz; bunların yerine geçmez.

**Diğer şıklar:** c) Sonucu küçük bir grupta tutmak, ilgili paydaşların öğrenmesini ve iyileştirmeden yararlanmasını kısıtlar. · d) Sorumlu ve takip tarihi zaten kararlaştırılmıştır. Aksiyon atamayı proje sonuna bırakmak iyileştirmeyi geciktirir.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Kaynak bilgi eksiği | LO: FL-2.1.6 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-6)

**Soru 27 — Doğru cevap: a**

**Neden doğru:** Yapısal kapsam, testlerin kodun ne kadarını çalıştırdığını nesnel bir ölçümle ifade eder. %85 dal kapsamı, testlerin kapsamlılığının bu boyutunu gösterir; doğruluğu veya tüm gereksinimlerin sağlandığını kanıtlamaz.

**En cazip yanlış (near-miss) — b:** Nesnel bir sayı ürün kalitesinin kanıtı gibi görünebilir. Fakat bir dalın çalıştırılması, davranışın doğru değerlendirildiği veya bütün gereksinimlerin sınandığı anlamına gelmez.

**Diğer şıklar:** c) Çalıştırılmayan dalların hatasızlığı hakkında bu ölçümden sonuç çıkarılamaz. · d) Yayım kararı için başka ölçütler ve riskler de değerlendirilir. Yüksek kapsam tek başına tamamlama kararı değildir.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.3.3 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-3)

**Soru 28 — Doğru cevap: c**

**Neden doğru:** Bütçe ve zaman kısıtları proje hedeflerini etkileyen proje riskleriyle ilgilidir. Yetkisiz erişim ise ürünün güvenliğine ilişkin ürün riskidir. Test süresinin azalması bu ürün riskine maruz kalmayı artırabilir; iki risk arasında neden ilişkisi bulunması onları aynı kategoriye dönüştürmez.

**En cazip yanlış (near-miss) — b:** Bütçe kararı erişim riskini artırdığı için aynı kategoriye aitmiş gibi görünebilir. Ancak sınıflandırma nedenine değil, tehdit edilen sonuca göre yapılır; erişim sorunu ürün kalitesiyle ilgilidir.

**Diğer şıklar:** a) Risk, gerçekleşmesi belirsiz olumsuz olayla ilgilidir. Henüz gerçekleşmemiş olması risk niteliğini ortadan kaldırmaz. · d) Ürün riskini değerlendirmek proje bütçesini ve kısıtlarını yönetme ihtiyacının yerine geçmez.

*Kaçırdıysanız tekrar edin: Risk yönetimi | Tuzak: Near-miss karışıklığı | LO: FL-5.2.2 (K2)*

[Kılavuzda tekrar edin: Risk yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-2-2)

**Soru 29 — Doğru cevap: a**

**Neden doğru:** Adım adım: 1. Dış boşluklar atıldığında ` harita ` girdisi `harita` olur; aynı öğenin dönmesi beklenir. 2. Kaydedilen sonuç boştur; gereksinimle fark buradadır. 3. `harita` başarılıdır; `h arita` ise iç boşluğu anlamlı olduğundan farklı kalır ve boş sonuç gereksinimle uyumludur. Rapor kanıtlanan farkı belirtmeli, doğrulanmamış bir kök neden ileri sürmemelidir.

**En cazip yanlış (near-miss) — d:** İki girdide de boşluk bulunduğu için aynı davranış beklenmesi caziptir. Ancak gereksinim dış ve iç boşlukları ayırır. İç boşlukları silmek verilen kural değildir.

**Diğer şıklar:** b) Gözlemi ters aktarır. Boşluksuz harita sorgusu başarısız değil, başarılıdır. · c) Veriler aramada bir uyumsuzluk gösterir. Veri tabanının bozulduğuna veya sorunun ayrıştırıcıdan kaynaklandığına dair kanıt yoktur.

*Kaçırdıysanız tekrar edin: Hata yönetimi | Tuzak: Prosedür hatası | LO: FL-5.5.1 (K3)*

[Kılavuzda tekrar edin: Hata yönetimi](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-5.html#fl-5-5-1)

**Soru 30 — Doğru cevap: b**

**Neden doğru:** Hata tahminleme, insan hataları, bunlardan doğabilecek ürün hataları ve arızalar hakkındaki genel bilgi ve tecrübeyi kullanabilir. Yeni uygulamanın kendi arıza geçmişinin bulunmaması tekniği kullanılamaz kılmaz.

**En cazip yanlış (near-miss) — a:** Geçmiş arızalar yararlı bir kaynak olduğu için caziptir. Ancak bilgi kaynağının mutlaka bu uygulamada önceden görülmüş bir arıza olması gerekmez.

**Diğer şıklar:** c) Dal sayıları yapısal kapsamla ilgilidir; öngörülen yanlışların yerine bunları koymak tecrübeye dayalı esası korumaz. · d) Öngörü bir test fikridir. Koşum veya başka kanıt olmadan doğrulanmış ürün hatası diye raporlanamaz.

*Kaçırdıysanız tekrar edin: Tecrübeye dayalı test teknikleri | Tuzak: Kaynak bilgi eksiği | LO: FL-4.4.1 (K2)*

[Kılavuzda tekrar edin: Tecrübeye dayalı test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-4-1)


### S31–S40

**Soru 31 — Doğru cevap: c**

**Neden doğru:** Testlerin esasını uzmanın sezgisi ve önceki deneyimleri oluşturur. Bu, tecrübeye dayalı test teknikleri (experience-based test techniques) kategorisidir. Kök belirtimden veya yapıdan türetmeyi dışarıda bırakır.

**En cazip yanlış (near-miss) — a:** Kod kullanılmadığı için kara kutu akla gelebilir. Ancak kara kutu tekniklerinde testler belirtim gibi dış davranışı tanımlayan kaynaklardan türetilir; burada esas tecrübedir.

**Diğer şıklar:** b) Beyaz kutu teknikleri kod veya başka bir iç yapıyı esas alır; kökte bu esas kullanılmamaktadır. · d) Risk bazlı test, risk bilgisinin test çalışmasını yönlendirmesidir. Kök risk değerlendirmesinden türetme anlatmaz.

*Kaçırdıysanız tekrar edin: Test tekniklerine genel bakış | Tuzak: Near-miss karışıklığı | LO: FL-4.1.1 (K2)*

[Kılavuzda tekrar edin: Test tekniklerine genel bakış](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-1-1)

**Soru 32 — Doğru cevap: d**

**Neden doğru:** Test, kararlaştırılan gereksinim ile ürün davranışını karşılaştırır ve dördüncü denemeye izin verilmesindeki arızayı ortaya çıkarabilir. Hata ayıklama bu arızaya yol açan hatayı bulup giderir. Beklentiyi yanlış davranışa uydurmak ürünü düzeltmez.

**En cazip yanlış (near-miss) — b:** Geçen bir test işin bittiği izlenimini verebilir. Burada geçen sonuç, gereksinime aykırı biçimde değiştirilmiş bir beklentiye dayanır; düzeltme ihtiyacını ortadan kaldırmaz.

**Diğer şıklar:** a) Ürün hatasını gidermek hata ayıklamanın işidir. Beklentiyi değiştirmek bu düzeltmenin karşılığı değildir. · c) Kararlaştırılmış gereksinim geçerliliğini korur. Gözlenen arızayı kabul etmek için sessizce yeniden tanımlanamaz.

*Kaçırdıysanız tekrar edin: Test nedir? | Tuzak: Near-miss karışıklığı | LO: FL-1.1.2 (K2)*

[Kılavuzda tekrar edin: Test nedir?](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-1-2)

**Soru 33 — Doğru cevap: b**

**Neden doğru:** Performans verimliliği ve güvenilirlik fonksiyonel olmayan özelliklerdir. Teslimat hattından gelen düzenli ölçümler, bu özelliklerdeki değişimleri daha görünür kılar. Bu, bütün gereksinimlerin sağlandığını veya bakım yükünün azaldığını kanıtlamaz.

**En cazip yanlış (near-miss) — a:** Sık kontroller ürüne güveni artırabileceği için caziptir. Ancak burada gözlenen fayda işlevsel gereksinimlerin tamamı değil, belirli fonksiyonel olmayan özellikler hakkındaki bilgidir.

**Diğer şıklar:** c) Kök kontrol bakımındaki efor hakkında veri vermez. Üründeki değişimler otomatik kontrollerde bakım gerektirebilir. · d) Önceki koşum, henüz sınanmamış değişikliklerin kaliteli olduğunu göstermez.

*Kaçırdıysanız tekrar edin: Yaşam döngüsü bağlamında test | Tuzak: Near-miss karışıklığı | LO: FL-2.1.4 (K2)*

[Kılavuzda tekrar edin: Yaşam döngüsü bağlamında test](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-1-4)

**Soru 34 — Doğru cevap: b**

**Neden doğru:** Statik test, iş ürünlerindeki hataları koşum başlamadan doğrudan ortaya çıkarabilir. Erken bulunan hataların düzeltilmesi, sonraki işlere yayılmadan yapılabildiği için daha düşük maliyetli olabilir. Statik ve dinamik test birbirini tamamlar.

**En cazip yanlış (near-miss) — a:** Her iki yaklaşım da hata tespitini desteklediği için caziptir. Ancak değer yalnız daha iyi belgeleme değildir; statik test dinamik testten farklı hatalar da bulabilir.

**Diğer şıklar:** c) Gözden geçirme, çalışma sırasındaki arızaları araştıran dinamik testin yerini bütünüyle almaz. · d) Gözden geçirme yapılması, kodun veya test koşumunun hızlanacağını göstermez.

*Kaçırdıysanız tekrar edin: Statik testin temelleri | Tuzak: Near-miss karışıklığı | LO: FL-3.1.2 (K2)*

[Kılavuzda tekrar edin: Statik testin temelleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-3.html#fl-3-1-2)

**Soru 35 — Doğru cevap: d**

**Neden doğru:** Dal testinde kapsam öğeleri dallardır. Yeni girdiler veya farklı yollar, yeni bir dal çalıştırmıyorsa kapsanan dal kümesini büyütmez. Bu nedenle kod da aynı kaldığında dal kapsama yüzdesi değişmez.

**En cazip yanlış (near-miss) — b:** Farklı yollar daha fazla test çeşitliliği sağlar; bu yüzden caziptir. Ancak yol ile dal aynı kapsam öğesi değildir. Aynı dallardan oluşan başka bir yol yeni dal kapsamı sağlamaz.

**Diğer şıklar:** a) Farklı girdiler tek başına yeni dal kapsandığını göstermez. Ölçülen öğe girdi değil daldır. · c) Grubun kapsamı tüm testlerin kapsadığı dalların birleşimidir; son testin kapsamı önceki dalları silmez.

*Kaçırdıysanız tekrar edin: Beyaz kutu test teknikleri | Tuzak: Near-miss karışıklığı | LO: FL-4.3.2 (K2)*

[Kılavuzda tekrar edin: Beyaz kutu test teknikleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-3-2)

**Soru 36 — Doğru cevap: d**

**Neden doğru:** Hata toleransı, güvenilirlik gibi fonksiyonel olmayan bir kalite özelliğiyle ilgilidir. Testler kaynak koddaki dallardan türetildiği için kullanılan esas yapısaldır: beyaz kutu testi (white-box testing). Amaç ile türetme esası ayrı boyutlardır.

**En cazip yanlış (near-miss) — b:** İki doğru sınıflandırmayı da içerdiği için caziptir. Ancak soru önce amacı, sonra türetme esasını ister; bu seçenekte sıra terstir.

**Diğer şıklar:** a) Yapısal esas doğru olsa da hata toleransını değerlendirme amacı fonksiyonel olarak sınıflandırılmıştır. · c) Amaç doğru sınıflandırılmıştır; ancak testler dış davranış belirtiminden değil kaynak kodun dallarından türetilmektedir.

*Kaçırdıysanız tekrar edin: Test seviyeleri ve test çeşitleri | Tuzak: Dikkatsiz okuma | LO: FL-2.2.2 (K2)*

[Kılavuzda tekrar edin: Test seviyeleri ve test çeşitleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-2.html#fl-2-2-2)

**Soru 37 — Doğru cevap: d**

**Neden doğru:** Kök iş değerinin, tahminlenebilirliğin, test edilebilirliğin ve küçük boyutun sağlandığını söyler. Ayrı teslim edilememe ise hikâyeler arasındaki bağımlılığa işaret eder; INVEST’in Independent özelliği ele alınmalıdır.

**En cazip yanlış (near-miss) — a:** Birbirine bağlı hikâyeler değerin teslimini zorlaştırabileceği için caziptir. Ancak hikâyenin iş değerinin açık olduğu zaten verilmiştir; eksik özellik bağımsızlıktır.

**Diğer şıklar:** b) Kök hikâyenin tahminlenebilir olduğunu söyler. Efor tahminlenememesi bu senaryonun sorunu değildir. · c) Kök hikâyenin test edilebilir olduğunu söyler. Teslim bağımlılığı bununla aynı özellik değildir.

*Kaçırdıysanız tekrar edin: İş birliğine dayalı test yaklaşımları | Tuzak: Near-miss karışıklığı | LO: FL-4.5.1 (K2)*

[Kılavuzda tekrar edin: İş birliğine dayalı test yaklaşımları](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-4.html#fl-4-5-1)

**Soru 38 — Doğru cevap: c**

**Neden doğru:** Araçlar iş ürününe ilişkin bulguların kaydedilmesine ve düzenlenmesine yardımcı olabilir. Değerlendirme insanlarda kalabilir. Statik test desteği, aracın yargıyı otomatik vermesini veya incelenen iş ürününü çalıştırmasını gerektirmez.

**En cazip yanlış (near-miss) — b:** Araç desteği insan yargısının otomatikleştirilmesiyle karıştırılabilir. Ancak bir aktiviteyi desteklemek, insanın onu daha düzenli yapmasına yardımcı olmak da olabilir.

**Diğer şıklar:** a) Dinamik test test nesnesini çalıştırır. Gereksinimleri incelemek için belge aracını kullanmak, gereksinimleri program olarak çalıştırmak değildir. · d) Araç, depoladığı verinin adıyla değil desteklediği aktiviteyle değerlendirilmelidir. Kök bir gereksinim gözden geçirmesi anlatır.

*Kaçırdıysanız tekrar edin: Test için araç desteği | Tuzak: Near-miss karışıklığı | LO: FL-6.1.1 (K2)*

[Kılavuzda tekrar edin: Test için araç desteği](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-6.html#fl-6-1-1)

**Soru 39 — Doğru cevap: b**

**Neden doğru:** Test nesnelerinin teknik özellikleri ve arayüzleri, ihtiyaç duyulan ortamı etkiler. Tarayıcı eklentisi ile aygıt yazılımı farklı teknik destek gerektirir. Ortak yaşam döngüsü ve benzer çalışan sayısı bu farkı açıklamaz.

**En cazip yanlış (near-miss) — a:** Yaşam döngüsü test sürecini etkileyebilir. Fakat karşılaştırmada iki ekip için aynı olduğu belirtilmiştir; ortamlardaki farkın açıklaması değildir.

**Diğer şıklar:** c) Çalışan sayısı süreci kısıtlayabilir; ürünün teknik arayüzlerini belirlemez. Ayrıca ekiplerin büyüklükleri benzerdir. · d) Ortam, test nesnesinin ihtiyaçlarına uygun olmalıdır. Ortak yaşam döngüsü her ürüne aynı ortamın uygun olduğunu göstermez.

*Kaçırdıysanız tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller | Tuzak: Near-miss karışıklığı | LO: FL-1.4.2 (K2)*

[Kılavuzda tekrar edin: Test aktiviteleri, test çalışma ürünleri ve roller](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-4-2)

**Soru 40 — Doğru cevap: c**

**Neden doğru:** Aynı testlerin değişmeden tekrarlanması yeni hata bulma gücünü azaltabilir. Buna rağmen uygun testlerin yeniden koşulması regresyonları ortaya çıkarabilir. Ekip bu faydayı korurken testlerini yeni hata olasılıklarına göre geliştirebilir. TTB ders programında ilke “antibiyotik direnci”, eski sürümde “pestisit paradoksu” adıyla da geçer; bu çalışmada kullanıcı kararıyla “testler yıpranır” kullanılır.

**En cazip yanlış (near-miss) — d:** Tekrarlanan başarılı sonuçlar güven verebilir. Ancak bu sonuçlar davranışın hatasız olduğunu kanıtlamaz; yalnız sınanan durumlar hakkında bilgi verir.

**Diğer şıklar:** a) Bilinen geçmiş sonuçlar, yeni veya değişen davranışları sınama ihtiyacını kaldırmaz. · b) Bir değişiklik daha önce çalışan davranışı bozabilir. Önceki başarı ilgili regresyon kontrolünü atlamayı haklı çıkarmaz.

*Kaçırdıysanız tekrar edin: Test prensipleri | Tuzak: Near-miss karışıklığı | LO: FL-1.3.1 (K2)*

[Kılavuzda tekrar edin: Test prensipleri](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/chapter-1.html#fl-1-3-1)


## Sınav günü kontrol listesi

- Sağlayıcınızın güncel sınav dilini, süreyi ve varsa ek süre hakkınızı kontrol edin.
- Kimlik ve teknik hazırlık koşullarını, bağlantı ve kamera gereksinimlerini tamamlayın.
- Başlamadan önce soru ve puanlama talimatlarını okuyun.
- Tek seçimli ve varsa çok seçimli sorularda istenen seçenek sayısına dikkat edin; bu denemenin bütün soruları tek seçimlidir.
- Uzayan soruyu işaretleyip süre izin veriyorsa geri dönün.
- Teslimden önce boş soruları ve işaretlediğiniz cevapları kontrol edin.

## Kaynakça

- ISTQB®, *Certified Tester Foundation Level Syllabus v4.0.1*, 15 Eylül 2024. Telif: ISTQB ve belgede belirtilen yazarlar. [Resmî CTFL sayfası](https://www.istqb.org/certifications/certified-tester-foundation-level-ctfl-v4-0/).
- ISTQB®, *Exam Structure Tables v1.18*, 27 Mayıs 2026; CTFL v4.0 tablosu. [ISTQB sınav belgeleri](https://www.istqb.org/).
- ISTQB®, *Exam Structures and Rules v1.2*, 2 Mayıs 2025. [ISTQB](https://www.istqb.org/).
- TTB, *Temel Seviye Ders Programı v4.0.1* Türkçe çevirisi ve *Yazılım Testi Terimler Sözlüğü v2*. [TTB hazırlık belgeleri](https://www.turkishtestingboard.org/foundation-level/).
- Kadir Çamoğlu, *ISTQB® CTFL® v4.0 Sınav Rehberi: Sıfırdan Sınava Hazır Seviyeye*, Türkçe kılavuz. [Türkçe kılavuz](https://kadir-camoglu.github.io/istqb-ctfl-v4-sinav-rehberi/).

CTFL v4.0.1 ders programı yazarları: Renzo Cerquozzi, Wim Decoutere, Jean-François Riverin, Arnika Hryszko, Martin Klonk, Meile Posthuma, Eric Riou du Cosquer, Adam Roman, Lucjan Stapp, Stephanie Ulrich ve Eshraka Zakaria. v4.0 yazarları ayrıca Klaudia Dussa-Zieger, Michaël Pilaeten ve Stuart Reid'i içerir. Ders programı ve bu belgeden kullanılan kavram adları ISTQB'nin hakları saklı materyalidir.

Sürüm: 19 Ekim 2026 · Geri bildirim: [kadir.camoglu@gmail.com](mailto:kadir.camoglu@gmail.com).

