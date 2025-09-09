# todo list
- study in your best way
- study monitor and tracking
- student statics for his level and progress also shown to tracher and parents
- habit tracker
- all in one platform (ekb nagaw stream links)
- motovation generator
- community
- import Minstry homework assaintments
- leader board
- tont assistant
- path finder

# gpt explain lsit
To-Do List / App Features

Smart Study Planner

طرق دراسة ذكية ومخصصة حسب كل طالب.

نصائح وتحفيزات شخصية لتحسين التركيز.

Study Monitor & Progress Tracking

متابعة ساعات الدراسة والمواد المنجزة.

إحصائيات توضح مستوى الطالب وتقدمه.

إمكانية عرض التقدم للمعلمين وأولياء الأمور.

Habit Tracker

متابعة العادات اليومية للطالب (مثلاً: مذاكرة، رياضة، نوم).

تنبيهات وتحفيز مستمر للحفاظ على العادات الجيدة.

All-in-One Platform

الوصول لجميع المصادر: كتب، فيديوهات، روابط Streams.

دمج كل الأدوات في مكان واحد لتسهيل التعلم.

Motivation Generator

اقتراح جمل تحفيزية، مقاطع فيديو، أو تحديات قصيرة.

Community

مساحة للتواصل مع طلاب آخرين.

مشاركة نصائح، خبرات، أو مساعدة بعضهم البعض.

Homework Importer

استيراد واجبات الوزارة تلقائياً لكل مادة.

تذكير وتنظيم الواجبات حسب المواعيد.

Leaderboard

ترتيب الطلاب حسب الأداء والتحصيل الدراسي.

تشجيع المنافسة الإيجابية والتحفيز.

AI Assistant

مساعد ذكي للإجابة على أسئلة الطالب.

اقتراح طرق دراسة، تنظيم وقت، أو حلول مشاكل دراسية.

Path Finder

اقتراح المسار الدراسي الأمثل حسب أهداف الطالب ومستواه.

تحديد نقاط القوة والضعف ووضع خطة تطويرية شخصية.



# gpt task list
1️⃣ Frontend (Repo: tont-frontend)

مسؤول: Frontend Developer

Tasks:

Landing Page / Homepage

تصميم واجهة المستخدم الرئيسية.

عرض المميزات الأساسية والاشتراك/تسجيل الدخول.

Student Dashboard

عرض الخطة الدراسية، المهام، الجدول، محتوى التعلم.

عرض الرسائل التحفيزية اليومية.

واجهة سهلة الاستخدام بالعربي/إنجليزي، دعم الوضع الليلي.

Teacher Dashboard

عرض متابعة الطلاب، التقييمات، الأداء العام.

Parent Dashboard

عرض التقدم، التنبيهات، المهام المنجزة.

All-in-One Content Page

دمج روابط Teams, YouTube, نجوى, بنك المعرفة.

واجهة بحث وتنظيم المواد بشكل مرتب.

Leaderboard / Gamification Page

عرض ترتيب الطلاب على مستوى الفصل/المدرسة.

Habit Tracker UI

صفحة لمتابعة العادات اليومية وبناء streaks.

Pathfinder / Career Guidance UI

واجهة أسئلة واختبارات لمساعدة الطالب على اختيار التخصص والمسار.

Chat-Tont UI

واجهة دردشة مع المساعد الذكي (يمكن لاحقًا ربطها بالـ AI).

2️⃣ Backend (Repo: tont-backend)

مسؤول: Backend Developer

Tasks:

User Management

تسجيل/تسجيل دخول الطالب، المعلم، ولي الأمر.

إدارة صلاحيات الوصول (Roles & Permissions).

Database Design & Setup

Tables: Users, Scores, Tasks, Habits, Messages, Content Links, Leaderboard, Pathfinding Data.

SQL-based database مع تشفير البيانات.

Study Tracking & Progress Monitoring

حفظ درجات الطلاب، الأخطاء، التقدم في المهام.

حساب النسب المئوية والتحليل الإحصائي.

Habit Tracker Backend

إنشاء وتحديث العادات اليومية.

حساب streaks وعرض إحصائيات.

Content Aggregation API

استيراد روابط Teams / YouTube / بنك المعرفة / نجوى.

واجهة API لإظهار المحتوى في الواجهة الأمامية.

Leaderboard API

حساب الترتيب على أساس الأداء.

API لتحديث وعرض القائمة في الوقت الحقيقي.

Pathfinder API

حفظ أسئلة الاختبارات وتحليل الإجابات.

اقتراح المسار الدراسي/المهنة المناسب للطالب.

Chat-Tont API (AI Integration)

ربط OpenAI أو Google API لشرح النقاط الصعبة وتنظيم الدراسة.

سجل محادثة الطالب مع المساعد الذكي.

3️⃣ Motivation & Notifications (Repo: tont-motivation)

مسؤول: Backend + Frontend integration

Tasks:

Daily Motivation Messages

رسائل تحفيزية تلقائية حسب أداء الطالب.

إرسال إشعارات عند هبوط الأداء أو غياب الطالب.

Push Notifications

تنبيهات بالمهام الجديدة، الواجبات، الرسائل التحفيزية.

تنبيهات لمواعيد الاختبارات والفروض.

4️⃣ Content Aggregation (Repo: tont-content)

مسؤول: Content Manager + Backend

Tasks:

جمع الروابط التعليمية من:

Teams

YouTube

بنك المعرفة المصري

منصة نجوى

تنظيم المحتوى حسب المواد والمستوى الدراسي.

تحديث دوري للمحتوى الجديد.

5️⃣ Homework & Evaluation (Repo: tont-homework)

مسؤول: Backend + Frontend

Tasks:

Homework Importer

إضافة الواجبات من مصادر الوزارة أو إدخالها يدويًا.

تنبيهات بالواجبات الجديدة وتواريخ التسليم.

Evaluation Tracker

حفظ النتائج، عرض التحسن أو التراجع.

عرض إحصائيات للطالب، المعلم، ولي الأمر.

6️⃣ AI & Pathfinder (Repo: tont-ai)

مسؤول: AI Developer

Tasks:

Chat-Tont

الرد على استفسارات الطالب الدراسية.

اقتراح طرق المذاكرة وتنظيم الوقت.

Pathfinder

تحليل نتائج الأسئلة لتحديد التخصص / المسار المناسب.

اقتراح أهداف قصيرة وطويلة المدى للطالب.
