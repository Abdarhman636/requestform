<template>
    <section id="RequestFormhtml">
        <header class="head-image"></header>
            <div class="container">
                <div class="wrapper">
                    <b-form action="https://formsubmit.co/contact@promoe.com.sa" method="POST">
                        <div class="form-group">
                        <label for="name" >Full Name</label>
                        <input type="text" class="form-control" id="name" name="name" placeholder="Example: Ahmed Hady Ibrahim" required>
                        <small for="">الاسم الثلاثي</small>
                        </div>

                        <div class="form-group">
                            <label for="phone">Mobile Phone</label>
                            <input type="text" class="form-control" id="phone" name="phone" placeholder="Example: +966 5511111111" required>
                            <label for="">رقم الهاتف</label>
                        </div>

                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" class="form-control" id="email" name="email" placeholder="Example: contact@promoe.com.sa" required>
                            <label for="">البريد الإلكتروني</label>
                        </div>

                        <div class="form-group">
                            <label for="website">Website</label>
                            <input type="text" class="form-control" id="website" name="website" placeholder="Example: https://promoe.com.sa">
                            <label for="">الموقع الإلكتروني</label>
                        </div>

                        <hr >

                        <div class="form-check">
                            <p>Project Type</p>
                            <input class="form-check-input" type="radio" name="project-type" value="brand" id="brand" checked>
                            <label class="form-check-label" for="brand">
                            Brand Identity
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="project-type" value="logo" id="logo">
                            <label class="form-check-label" for="logo">
                            Logo
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="project-typse" value="packaging" id="packaging">
                            <label class="form-check-label" for="packaging">
                            Packaging
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="radio" name="project-type" value="posts" id="posts">
                            <label class="form-check-label" for="posts">
                            Posts Design 
                            </label>
                        </div>

                        <hr >

                        <div class="form-group">
                            <label for="project-name">Project Name</label>
                            <input type="text" class="form-control" id="project-name" name="project-name" placeholder="Example: Shot Coffeeshop">
                            <label for="">Please, write project name in Arabic and English | إسم المشروع بالعربي والانجليزي</label>
                        </div>

                        <label for="">Project Type</label>
                        <select class="form-select" aria-label="Default select example">
                            <option selected value="food">Cafe | مقهى</option>
                            <option value="realstate">Resturant | مطعم</option>
                            <option value="advertising">Real State | عقارات</option>
                            <option value="other">Food | طعام</option>
                            <option value="other">Products | منتجات</option>
                            <option value="other">Services | خدمات</option>
                            <option value="other">Technique | تقنية</option>
                            <option value="other">Other | اخر</option>
                        </select>

                        <div class="mb-3">
                            <label for="aboutproject" class="form-label">About Project</label>
                            <textarea class="form-control" id="aboutproject" name="aboutproject" rows="3"></textarea>
                            <label class="form-label">نبذة عن المشروع وجميع التفاصيل</label>
                        </div>

                        <p>Target</p>
                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="kids" name="kids" value="kids">
                            <label class="form-check-label" for="kids">KIDS | اطفال</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="youth" name="youth" value="youth">
                            <label class="form-check-label" for="youth">YOUTH | شباب</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="adults" name="adults" value="adults">
                            <label class="form-check-label" for="adults">ADULTS | بالغين</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="women" name="women" value="women">
                            <label class="form-check-label" for="women">WOMEN | نساء</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="checkbox" id="men" name="men" value="men">
                            <label class="form-check-label" for="men">MEN | رجال</label>
                        </div>

                        <div class="form-group">
                            <label for="project-color">WHICH COLORS DO YOU PREFER ?</label>
                            <input type="text" class="form-control" id="project-color" name="project-color" placeholder="Example: black and yellow">
                            <label for="">ماهي الالوان التي تفضلها ؟</label>
                        </div>

                        <hr >

                        <h6>HOW MANY DESIGN OPTIONS DO YOU WANT?</h6>
                        <div class="fsorm-check form-check-inline">
                            <input class="form-check-input" type="radio" name="design-option" id="2design" value="2designs" checked>
                            <label class="form-check-label" for="2designs">2</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="design-option" id="3designs" value="3designs">
                            <label class="form-check-label" for="3designs">3</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="design-option" id="4designs" value="4designs">
                            <label class="form-check-label" for="4designs">4</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="design-option" id="5designs" value="5designs">
                            <label class="form-check-label" for="5designs">5</label>
                        </div>

                        <p>كم خيار تصميم تحتاج ؟</p>

                        <h6>LOGO TYPE</h6>
                        <div class="fsorm-check form-check-inline">
                            <input class="form-check-input" type="radio" name="logo-type" id="ICONIC" value="ICONIC" checked>
                            <label class="form-check-label" for="ICONICs">ICONIC</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="logo-type" id="TYPEFACE" value="TYPEFACE">
                            <label class="form-check-label" for="TYPEFACE">TYPEFACE</label>
                        </div>

                        <div class="form-check form-check-inline">
                            <input class="form-check-input" type="radio" name="logo-type" id="ARABICCALLIGRAPHY" value="ARABICCALLIGRAPHY">
                            <label class="form-check-label" for="ARABICCALLIGRAPHY">ARABIC CALLIGRAPHY</label>
                        </div>

                        <p>اي نوع شعار تفضل ؟</p>

                        <h6>BRAND APPLICATIONS</h6>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="BUSINESS CARD | الكروت الشخصية" id="business" name="business" checked>
                            <label class="form-check-label" for="business">
                            BUSINESS CARD | الكروت الشخصية
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="LETTER HEAD | الورقة الرسمية" id="letterhead" name="letterhead">
                            <label class="form-check-label" for="letterhead">
                            LETTER HEAD | الورقة الرسمية
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="DL ENVELOPE | ظرف الرسائل" id="envelope" name="envelope">
                            <label class="form-check-label" for="envelope">
                            DL ENVELOPE | ظرف الرسائل
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="A5 ENVELOP | ظرف حجم صغير" id="envelopea5" name="envelopea5">
                            <label class="form-check-label" for="envelopea5">
                            A5 ENVELOP | ظرف حجم صغير
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="A4 ENVELOP | ظرف حجم وسط" id="letterheada4" name="letterheada4">
                            <label class="form-check-label" for="letterheada4">
                            A4 ENVELOP | ظرف حجم وسط
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="A3 ENVELOP | ظرف حجم كبير" id="letterheada3" name="letterheada3">
                            <label class="form-check-label" for="letterheada3">
                            A3 ENVELOP | ظرف حجم كبير
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="FOLDER FOR ALL STATIONARY | ملف الاوراق" id="folder" name="folder">
                            <label class="form-check-label" for="folder">
                            FOLDER FOR ALL STATIONARY | ملف الاوراق
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="COMPLIMENT CARD | بطاقة تهنئة" id="ccard" name="ccard">
                            <label class="form-check-label" for="ccard">
                            COMPLIMENT CARD | بطاقة تهنئة
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="CD & CD COVER | القرص الصلب مع الظرف" id="cdcover" name="cdcover">
                            <label class="form-check-label" for="cdcover">
                            CD & CD COVER | القرص الصلب مع الظرف
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="PAPER BAG | الكيس الورقي" id="paperbag" name="paperbag">
                            <label class="form-check-label" for="paperbag">
                            PAPER BAG | الكيس الورقي
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="CAR | سيارة" id="car" name="car">
                            <label class="form-check-label" for="car">
                            CAR | سيارة
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="SIGN BOARD | اعلان المحل" id="signboard" name="signboard">
                            <label class="form-check-label" for="signboard">
                            SIGN BOARD | اعلان المحل
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="BASIC BRAND GUIDELINE | كتيب خاص لطريقة استخدام الهوية التجارية . مبسط" id="basicbrandguideline" name="basicbrandguideline">
                            <label class="form-check-label" for="basicbrandguideline">
                            BASIC BRAND GUIDELINE | كتيب خاص لطريقة استخدام الهوية التجارية . مبسط
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="T.SHIRT | الفانيلات" id="tshirt" name="tshirt">
                            <label class="form-check-label" for="tshirt">
                            T.SHIRT | الفانيلات
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="ROLL UP | رول آب" id="rollup" name="rollup">
                            <label class="form-check-label" for="rollup">
                            ROLL UP | رول آب
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="NOTEPAD | دفتر الملاحظات" id="notepad" name="notepad">
                            <label class="form-check-label" for="notepad">
                            NOTEPAD | دفتر الملاحظات
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="PEN | قلم" id="pen" name="pen">
                            <label class="form-check-label" for="pen">
                            PEN | قلم
                            </label>
                        </div>

                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="SOCIAL MEDIA (TEMPLATES) | تصميم عام لمواقع التواصل الاجتماعي" id="solcialmediat" name="solcialmediat">
                            <label class="form-check-label" for="solcialmediat">
                            SOCIAL MEDIA (TEMPLATES) | تصميم عام لمواقع التواصل الاجتماعي
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="POWERPOINT (TEMPLATES)" id="powerpoint" name="solcialmediat">
                            <label class="form-check-label" for="powerpoint">
                            POWERPOINT (TEMPLATES)
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="BROCHURE (TEMPLATES) | تصميم عام للكتيب" id="brochure" name="brochure">
                            <label class="form-check-label" for="brochure">
                            BROCHURE (TEMPLATES) | تصميم عام للكتيب
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="PRESS AD (TEMPLATES) | تصميم عام للاعلانات" id="pressad" name="pressad">
                            <label class="form-check-label" for="pressad">
                            PRESS AD (TEMPLATES) | تصميم عام للاعلانات
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="WEBSITE TEMPLATE (TEMPLATES) | تصميم عام للموقع" id="websitetem" name="websitetem">
                            <label class="form-check-label" for="websitetem">
                            WEBSITE TEMPLATE (TEMPLATES) | تصميم عام للموقع
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="WRAPPING PAPER | ورق التغليف" id="wrappingpaper" name="wrappingpaper">
                            <label class="form-check-label" for="wrappingpaper">
                            WRAPPING PAPER | ورق التغليف
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="POSTER | الملصق" id="poster" name="poster">
                            <label class="form-check-label" for="poster">
                            POSTER | الملصق
                            </label>
                        </div>
                        <div class="form-check">
                            <input class="form-check-input" type="checkbox" value="BRAND GUIDELINE | كتيب خاص لطريقة استخدام الهوية التجارية . مفصل" id="brandguidline" name="brandguidline">
                            <label class="form-check-label" for="brandguidline">
                            BRAND GUIDELINE | كتيب خاص لطريقة استخدام الهوية التجارية . مفصل
                            </label>
                        </div>
                        
                        <div class="form-group">
                            <label for="other-application">Other Applications?</label>
                            <input type="text" class="form-control" id="other-application" name="other-application">
                            <label for="">تطبيقات اخرى</label>
                        </div>

                        <hr >

                        <div class="form-group">
                            <label for="project-budget">Project Budget</label>
                            <input type="text" class="form-control" id="project-budget" name="project-budget">
                            <label for="">الميزانية الموضوعة للعمل بالريال السعودي</label>
                        </div>

                        <hr >

                        <p>Upload any file related to the project</p>
                        <div class="input-group mb-3">
                            <input type="file" class="form-control" id="inputGroupFile02" name="inputGroupFile02">
                            <label class="input-group-text" for="inputGroupFile02">Upload</label>
                        </div>
                        <p>Example, the old logo or images of the project or logos you liked | إرفق اي ملفات نحتاج اليها في العمل الخاص بك ، مثل مخطوطات اعجبتك او شعارك القديم وهكذا</p>

                        <button type="submit" class="btn btn-primary">Submit</button>
                    </b-form>
                </div>
            </div>
    </section>
</template>

<script>

export default {
    name: 'RequestFormhtml',
}
</script>