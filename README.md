## Git və GithUb Qeydlərim

Git sistemində qeydiyyatdan keçmək

```
git config --global user.name "İstifadəçi adı"
git config --global user.email "Elektron poçt adresi"
```
Qeydiyyatı check etmək

```
git config --global user.name
git config --global user.email
```
Localda olduğumu adresi yoxlamaq
```
cd
```
Localdakı adresimizdə olan fayllara baxmaq
```
ls
```
Localdakı adresimizi dəyişmək
```
cd "getmək istədiyimiz adres"
```
Localda olduğumuz adresdən geri qayıtmaq
```
cd ..
```
Localdakı layihəmizin adresində Giti quraşdıracaq faylları yükləmək
```
git init
```
Qovluqdakı bütün faylları Git sistemindəki Keçid Ərazisinə (Staging Area) əlavə etmək
```
git add .
```
Qovluqdakı hər hansı bir faylı Git sistemindəki Keçid Ərazisinə (Staging Area) əlavə etmək
```
git add . faylın_adı.faylın_tipi
```
Keçid ərazisindən Repoya (Git Repository) commit etmək
```
git commit -m "Qeyd"
```
Cari branchın versiyalama tarixçəsini siyahılandırma
```
git log
```
Commit edilmiş yeni və ya dəyişdirilən faylların siyahılandırılması
```
git status
```
Local ilə repodakı bütün faylların fərqlərini siyahılandırmaq
```
git diff
```
Local ilə repodakı faylın fərqini siyahılandırmaq
```
git diff faylın_adı.faylın_tipi
```
Keçid ərazisi ilə repodakı bütün faylların fərqlərini siyahılandırmaq
```
git diff
```
Keçid ərazisi ilə repodakı faylın fərqini siyahılandırmaq
```
git diff faylın_adı.faylın_tipi
```
Faylı silmək
```
git rm faylın_adı.faylın_tipi
```
Qovluğu silmək
```
git rm -r qovluğun_adı/
```
Faylın adını dəyişmək
```
git mv kohne_ad.faylın_tipi yeni_ad.faylın_tipi
```
Faylı başqa bir qovluğa köçürmək
```
git mv faylın_adı.faylın_tipi qovluğun_adı/
```
Localdakı faylın dəyişiklikləri geri qaytarmaq
```
git checkout -- faylın_adı
```
Keçid ərazisindəki faylın dəyişiklikləri geri qaytarmaq
```
git reset HEAD faylın_adı
git checkout -- faylın_adı
```
Əvvəlki versiyaya qayıtmaq
```
git checkout -- version_commit_hash -- .
```
Faylı GitHubdakı repoya əlavə etmək
```
git remote add reponun_adı reponun_linki
git push -u reponun_adı branchın_adı
```
