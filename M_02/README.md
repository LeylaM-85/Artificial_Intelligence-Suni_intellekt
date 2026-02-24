1. Süni intellektdə PROQNOZLAŞDIRMA
Layihənin məqsədi: Evlərin sahəsinə (kvadrat metr) əsasən onların qiymətini proqnozlaşdıran sadə bir reqressiya modeli.
Maşın Öyrənməsi növü: Bu, nəzarətli öyrənmənin (supervised learning) bir növü olan xətti reqressiya (linear regression) modelidir.

2. İstifadə Olunan Kitabxanalar
NumPy: Çoxölçülü massivlərlə sürətli riyazi əməliyyatlar aparmaq üçün.
Scikit-learn: Maşın öyrənməsi modellərini qurmaq, təlim etmək və proqnozlar vermək üçün.
Matplotlib: Məlumatları və proqnoz xəttini vizuallaşdırmaq üçün.
SciPy: Elmi və texniki hesablamalar, həmçinin statistik analizlər üçün.

3. Quraşdırma Təlimatları
Kodu yerli mühitdə (local environment) işlətmək istəyənlər üçün terminalda lazım olan əmrləri yaza bilərsiz
Kitabxanaları quraşdırmaq üçün: pip install numpy scikit-learn matplotlib scipy.
Google Colab - bu kitabxanalar artıq quraşdırılmış olur və əlavə yükləməyə ehtiyac yoxdur.

4. Kodun İş Prinsipləri
Məlumatların Hazırlanması: Giriş məlumatlarının (features - X) reshape(-1, 1) metodu ilə sütun şəklində ikiölçülü massivə çevrilməsi.
Modelin Təlimi: model.fit(X, Y) funksiyası ilə modelin giriş və çıxış məlumatları arasındakı əlaqəni öyrənməsi.
Proqnoz: model.predict() vasitəsilə yeni sahə dəyərləri üçün qiymətin təyin edilməsi.

5. Vizuallaşdırma
Modelin nəticələrini görə bilərik
Real məlumat nöqtələri (scatter plot) və modelin öyrəndiyi proqnoz xəttinin (line plot) bir qrafikdə göstərilməsi.
