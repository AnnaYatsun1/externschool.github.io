# Пользовательские истории MVP
### черновой вариант для доработки

***
**Термины**<br>
*Сотрудник школы*: 
1) *Должностное лицо* -- в соответствии с занимаемой должностью выполняет административные (директор, зам. по младшей школе, зам. по старшей школе) или вспомогательные функции (психолог);
2) *Дежурный учитель/администратор* -- абстрактное лицо, организатор проведения контрольных работ;
3) *Учитель* -- участвует в образовательном процессе, непосредственно контактирует с Учениками.
<br> Указанные функции могут совмещаться одним лицом. 

*Администратор школы* - лицо, управляющее расписанием и записью на прием к Сотрудникам школы (школьный секретарь, должностные лица, дежурный учитель/администратор).

*Гость* -- посетитель, который появляется в школе для решения отдельных задач: например, узнать об условиях приема, сдать нужные документы, получить зачетную книжку для ребенка и т.п.

*Ученик* -- посетитель, который во время учебы неоднократно контактирует с разными Учителями, получает у них консультации; пишет контрольные работы.

*Pасписание* -- календарь, для которого указана информация о доступном времени для проведения встреч с Сотрудниками школы (консультация, беседа с директором, психологом, написание контрольных работ и т.п.).

*График проведения контрольных работ* -- расписание абстрактного дежурного учителя/администратора. Составляется и поддерживается Админстратором школы без указания конкретных исполнителей роли дежурного учителя/администратора. В отличие от расписаний Учителей учитывает количество мест на каждый интервал.

*** 
**Учителя**

как Учитель, я могу создать свое расписание, чтобы посетители могли назначать встречи со мной согласно этому расписанию.

как Учитель, я могу иметь возможность назначить приемное время на определенные дни недели, в определенные промежутки времени с установленной мною длительностью, чтобы структурировать мое расписание.

как Учитель, я хочу, чтобы мое расписание учитывало календарные выходные и праздничные дни, начиналось и заканчивалось в определенные дни учебного года (не ранее 1 сентября и не позднее 31 мая -- задается в настройках), чтобы расписание учитывало время работы школы (с 9-00 до 19-00 -- задается в настройках). 

как Учитель, я могу просматривать расписание любого Учителя.

как Учитель, я могу просматривать график проведения контрольных работ.

как Учитель, я могу просматривать, кто записан ко мне на прием на определенный день с указанием времени записи, чтобы лучше организовать свое время в этот день, для каждой записи я хочу видеть ФИО Ученика, класс в котором он учится, школьный предмет, по которому он собирается со мной общаться, средства связи с ним (телефон, почтовый ящик), чтобы быть готовым к встрече. 

*Опционально* как Учитель, я могу сформировать и сохранить список тех, кто записан ко мне на определенный день (ФИО Ученика, класс, предмет, средства связи), ранжировав посетителей по времени посещения, чтобы лучше организовать свое время в этот день. 

как Учитель, я могу внести изменения в расписание, чтобы оно отражало реальное положение вещей в случае моей болезни, командировки или любой другой причины, изменяющей мой рабочий график. Требуется указать причину внесения изменений. Если есть записанные на это время Ученики, на их почтовые ящики должны быть отправлены письма с уведомлением об отмене консультации и указанием причины.

*Опционально* как Учитель, я хочу иметь возможность выбора (получать или не получать) уведомления на мой почтовый ящик в случае, если назначенная Учеником встреча будет отменена. 

***
**Администратор школы**

как Администратор, я могу создать расписание для любого должностного лица школы, чтобы посетители могли записаться к нему на прием.

как Администратор, я могу иметь возможность назначить приемное время должностного лица школы на определенные дни недели, в определенные промежутки времени с установленной длительностью, чтобы структурировать расписание должностного лица.

как Администратор, я хочу, чтобы расписание должностного лица школы учитывало календарные выходные и праздничные дни, начиналось и заканчивалось в определенный день года учебного года (не ранее 1 августа и не позднее 15 июня -- задается в настройках), чтобы расписание учитывало время работы школы (с 9-00 до 18-00 -- задается в настройках). 

как Администратор, я могу просматривать в системе, кто записан к должностным лицам школы (директор, зам. по младшей школе, зам. по старшей школе, психолог) на прием в определенный день и время, чтобы помочь организовать их время в этот день. 

как Администратор, я хочу видеть список посетителей к любому должностному лицу школы на определенный день и время с указанием для каждого: имени и фамилии, причины встречи, средств связи (номер телефона и почтовый ящик). Я хочу иметь возможность сохранить такой список, чтобы в дальнейшем с ним работать вне системы. 

как Администратор, я могу редактировать расписание для любого должностного лица школы, чтобы об изменениях уведомить посетителей, на момент редактирования уже записанных к нему на прием. Мне потребуется указать причину отмены предварительной записи.

как Администратор, я могу создать графики проведения контрольных работ, чтобы обозначить дни, время и количество мест, доступные для записи на написание контрольных работ. 

как Администратор, я могу редактировать график проведения контрольных работ на любую предстоящую дату и время. Если на момент редактирования есть записи Учеников на написание контрольных работ, на их почтовые ящики должны быть отправлены письма с соответствующим уведомлением.

как Администратор, я хочу видеть список Учеников на написание контрольных работ в определенный день и время. Я хочу иметь возможность сохранить такой список, чтобы в дальнейшем с ним работать вне системы. Для каждой записи на написание контрольных работ я хочу видеть ФИО Ученика, класс в котором он учится, школьный предмет, семестр, за который он пишет контрольную, фамилию Учителя, которому передать написанную контрольную, средства связи (телефон, почтовый ящик).

***
**Гость**

как Гость, я могу выбрать из списка нужное мне должностное лицо, чтобы просмотреть его расписание с указанием доступного для записи времени.

как Гость, я могу записаться к выбранному Сотруднику школы на прием в удобное для меня и доступное в его расписании время, чтобы решить интересующие меня вопросы. 
Требуется указать: фамилию, имя, отчество, причину встречи, номер телефона в качестве идентификатора (чтобы можно было отменить запись), почтовый ящик для отправки уведомлений в случае изменений в расписании. 

*Опционально* как Гость, я могу отменить свою встречу, чтобы освободить время, зарезервированное за мной, для другого посетителя.
Требуется идентификация по номеру телефона.

*Опционально* как Гость, я хочу получать уведомления на указанный мной почтовый ящик в случае, если моя встреча будет отменена.

*Опционально* как Гость, я могу иметь возможность просмотреть график проведения контрольных работ с указанием доступного для записи количества мест.

*Опционально* как Гость, я могу выбрать из списка любого Учителя, чтобы просмотреть его расписание.

***
**Ученик**

как Ученик, я хочу иметь возможность зарегистрироваться в системе, чтобы просматривать назначенные мной встречи.<br>
**Пример детализации**<br>
Нужны: почтовый адрес, имя пользователя, пароль, уникальный идентификатор(ключ).<br>
Тест 1: пользователь не может ввести пароль меньше 6 символов.<br>
Тест 2: пользователь не может ввести имя, длиной меньше 3 и больше 20 символов.<br>
Тест 3: пользователь должен иметь уникальное имя в системе.<br>
Тест 4: при регистрации пользователь должен ввести уникальный идентификатор(ключ), полученный в школе, который привяжет его учетную запись к реальному ученику школы. <br>
Тест 5: после регистрации пользователь должен получить на свой почтовый ящик подтверждение активации учетной записи.<br>
Тест 6: пользователь не может войти в систему с правами Ученика, если учетная запись не активирована.<br>
Тест 7: при успешном входе пользователь приветствуется текстом "Добро пожаловать, <Имя ученика, привязанное к учетной записи>!".<br>

как Ученик, я могу иметь возможность выбрать из списка Учителяей нужного мне, чтобы просмотреть его расписание.

как Ученик, я могу иметь возможность записаться к выбранному Учителю на прием в удобное для меня и доступное в его расписании время, чтобы получить консультацию. Я должен указать предмет, по которому получаю консультацию.

как Ученик, я могу просмотреть график проведения контрольных работ с указанием доступного для записи количества мест.

как Ученик, я могу записаться на доступное в графике проведения контрольных работ время (если есть свободные места), чтобы написать контрольную работу. Запись уменьшает количество свободных мест на выбранное время. При записи я должен указать: школьный предмет, семестр, за который пишется контрольная, фамилию Учителя, которому передать написанную контрольную.

как Ученик, я могу просматривать назначенные мной встречи с указанием даты и времени встречи, Учителя, к которому я записан, учебного предмета. 

как Ученик, я могу просматривать назначенные мной записи на контрольную работу с указанием даты, времени, предмета, семестра и Учителя, которому будет направлена на проверку моя работа.

*Опционально* как Ученик, я могу отменить свою встречу с Учителем, чтобы освободить время, зарезервированное за мной, для другого посетителя. Освобожденный временной интервал становится доступен для выбора другим пользователем.

*Опционально* как Ученик, я могу отменить свою запись на контрольную работу, чтобы освободить время, зарезервированное за мной, для другого посетителя. Отмена записи увеличивает количество свободных мест на выбранное время.

*Опционально* как Ученик, я хочу получать уведомления на указанный мной почтовый ящик в случае, если моя встреча с Учителем или запись на контрольную работу будет отменена.
