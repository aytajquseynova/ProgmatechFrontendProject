# Javascript proqramlaşdırma dili hansı sahələrdə istifadə olunur?
1.Web sayta interaktivlik verməkçün istifadə olunur,
2.Oyunlar yazılır,
3.Veb və mobil app`lərin yaradılmasında
# Proqramlaşdırma terminlərinin qısa açıqlamaları
* compilers-Bir proqramlaşdırma dilində yazılmış kodu başqa proqramlaşdırma dilinə çevirir.(Yüksək səvviyə bir dildən aşağı səviyyə bir dilə)Hər hansı proqramlaşdırma dilini istifadə edərək yazılan kodu kompüterin anlaya biləcəyi maşın dilinə 0-1-lərə çevirən yazılımdır. 
Microsoft Visual Studio
GNU Compiler Collection (GCC)
Common Business Oriented Language (COBOL)
* interpreters-Kodu parçalar halında dəyərləndirmək məqsədilə istifadə olunur.Kodu sətir ya da blok şəklində çalışdırırlar.
OCaml
List Processing (LISP)
Python
* translators- 3 fərqli translator tipi var. Bunlar compiler, interpreter və assemblerdir. Compiler, interpreter terminlərindən yuxarıda qısaca bəhs etdik. Assembler termini haqqında da aşağıda məlumat veriləcək.
* assemblers -Fortran Assembly Program (FAP)
Macro Assembly Program (MAP)
Symbolic Optimal Assembly Program (SOAP)
Avantajları- proqramlaşdırma üçün zaman təsərrüfü yaradır.
Xətaları düzəltmək, həmçinin proqramlaşdırma təlimatların dəyişdirmək daha asandır.
Dezavantaj olaraq isə onu qeyd edə bilərəm ki, kiçik bir dəyişiklik belə proqramı keçərsizləşdirə bilər. Baxımı çətindir.

* programming paradigms- proqram dillərini özəlliklərinə görə sinifləndirmənin bir yoludur.2 yerə bölünür: imperativ və deklarativ. İmperativ proqramlaşdırma dillərinə Pascal, Java, C dillərini nümunə göstərə bilərik.Deklarativ proqramlaşdırma dillərinə isə nümunə göstərməli olsaq,Prolog,Lisp, Haskell, Miranda, Erlang,SQL (in the broadest sense) adların çəkə bilərik.

* debugging- kodlarınızdakı xətaları tapmağa, analiz etməyə kömək edir. kodlardakı xətalar "bug"lardır.
* boolean- Başqa tip verilənlərdən fərqli olaraq, Boolean tipli dəyişən yalnız iki qiymət ala bilər: True (doğru) və False (yalan).
Proqramlarda bu tipli dəyişənlərdən müəyyən qərar qəbul etmək lazım gəldikdə istifadə etmək olar.
Boolean tipli qiymətləri ekrana çıxarmaq olar, ancaq belə qiymətləri klaviaturadan daxil etmək olmaz. Bu tip dəyişənlər üzərində not (deyil), and (və), və or (və ya) əməllərini yerinə yetirmək olar.
* char-Char və Varchar, verilənlər bazası sistemində oxşar görünən, saxlama tələblərinə gəldikdə aralarında fərqlər olsa da çox istifadə olunan xarakter məlumat növləridir. char məlumat növü bir xarakter saxlamaq üçün istifadə olunur . Char (n) n sabit ölçüdə simvol saxlaya bilər. Bir char (n) -in tuta biləcəyi maksimum simvol sayı 255 simvol və bir simli uzunluğu 1 ilə 8000 arasında bir dəyər olmalıdır. Char varchar -dan əlli faiz daha sürətlidir və buna görə də işləyərkən daha yaxşı bir performans əldə edə bilərik. char Char məlumat saxlayarkən statik yaddaş ayırmasını istifadə edir. Bilinən sabit uzunluğa malik sətirləri saxlamaq istədikdə, char istifadə etmək daha yaxşıdır. Nümunə olaraq, 'Bəli' və 'Xeyr' -i 'Y' və 'N' olaraq saxlayarkən char tipli məlumat tipindən istifadə edə bilərik. Həm də bir şəxsin milli şəxsiyyət vəsiqəsi nömrəsini on simvoldan saxlayarkən məlumat növünü char (10) olaraq istifadə edə bilərik.
* null- Verilənlər bazasında sıfır bir dəyərdir. Null dəyər heç bir dəyəri olmadığını bildirir.Bir dəyər kimi istifadə edildikdə, null bir yaddaş yeri deyil. Yalnız göstəricilər yaddaş yerlərini saxlayır. Null bir xarakter olmadan, simli düzgün bir şəkildə sona çatmayacaq, bu da problemə səbəb olacaq.
* command-line interface- komanda sətri interfeysi. Komanda xəttinin tərcüməsi əmrlərin daxil olmasına imkan verən və bu əmrləri əməliyyat sisteminə tətbiq edən hər hansı bir proqramdır. Sözün əslində bir komanda tercümanı var. Bir siçanla idarə olunan düymələr və menyular kimi bir qrafik istifadəçi interfeysi (GUI) olan bir proqramdan fərqli olaraq, bir komanda satırı tərcüməçi komanda kimi klaviaturadan mətn xətlərini qəbul edir və bu əmrləri əməliyyat sisteminin anladığı funksiyalara çevirir.
* low-level language- Aşağı səviyyəli dillər kompilyator və ya tərcüməçi olmadan maşın koduna çevrilə bilər. Aşağı səviyyəli dillər sadədir, lakin proqramçının yadda saxlamalı olduğu çoxsaylı texniki detallara görə istifadəsi çətin hesab olunur.
* high-level language- Python, Visual Basic, Delphi, Perl, PHP, ECMAScript, Ruby, C#, Java. Proqramçı artıq sadəcə problemin həllinə fokuslanır və daha az əmr istifadə edərək proqramı yaza bilir. Həmçinin bu dilləərdə yazılan əmrlərin insanların daha rahat anlaya biləcəyi və ağılda qalacağı bir haldadır. 
* markup language- BBC, HTML, SGML,  XML. nümunə olaraq bunları saya bilərəm.Səhifənin ümumi görünüşünü və onun ehtiva etdiyi məlumatı formatlamağa kömək edən asan başa düşülən açar sözlər, adlar və ya etiketlərdən ibarət kompüter dili 