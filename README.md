# Objectives (Темы)

## Study points for the exam (Пункты оценки на экзамене)

RHCSA exam candidates should be able to accomplish the tasks below without assistance. These have been grouped into several categories.
(*Кандидаты на экзамен RHCSA должны быть в состоянии выполнить перечисленные ниже задачи без посторонней помощи. Они были сгруппированы в несколько категорий.*)

### Understand and use essential tools (Понимание и использование основных инструментов)

- Access a shell prompt and issue commands with correct syntax (*Доступ к приглашению командной строки и выполнение команд с правильным синтаксисом*)
- Use input-output redirection (>, >>, |, 2>, etc.) (*Использованеи перенаправление ввода-вывода*)
- Use grep and regular expressions to analyze text (*Использование grep и регулряных выражений для анализа текста*)
- Access remote systems using SSH (*Удаленный доступ с использованием SSH*)
- Log in and switch users in multiuser targets (*Вход и пререключение пользователей в многопользовтальских средах*)
- Archive, compress, unpack, and uncompress files using tar, star, gzip, and bzip2 (*Архивация, сжатие, распаковка и декомпрессия файлов используя tar, star, gzip, и bzip2*)
- Create and edit text files (*Создание и редактирование текстовых файлов*)
- Create, delete, copy, and move files and directories (*Создание, удаление, копирование и перемещений фйалов и директорий*)
- Create hard and soft links (*создание софт и хардлинков*)
- List, set, and change standard ugo/rwx permissions (*Просмотр, назначение и изменение разрешений ugo/rwx*)
- Locate, read, and use system documentation including man, info, and files in /usr/share/ doc (*Поиск, чтение и использование системной докуументации включая man, info и файлы в /usr/share/*)

### Create simple shell scripts (*Создание простых shell-скриптов*)

- Conditionally execute code (use of: if, test, [], etc.) (**)
- Use Looping constructs (for, etc.) to process file, command line input (**)
- Process script inputs ($1, $2, etc.) (**)
- Processing output of shell commands within a script (**)

### Operate running systems (обслуживание работающих систем)

- Boot, reboot, and shut down a system normally (*Загрузка, перезагрузка и выключение системы в штатном режиме*)
- Boot systems into different targets manually (*Загрузка систем в различных режимах вручную*)
- Interrupt the boot process in order to gain access to a system (*Прерывание процесса загрузки для получения доступа к системе*)
- Identify CPU/memory intensive processes and kill processes (*Идентификация процессов интенст*)
- Adjust process scheduling (*Настрйока планирования процессов*)
- Manage tuning profiles (*Управление профилями настройки*)
- Locate and interpret system log files and journals (*Расположение и интерпретация файлов системных журналов*)
- Preserve system journals (*Просмотр системных журналов*)
- Start, stop, and check the status of network services (*Запуск, остановка, и проверка статуса сетевых сервисов*)
- Securely transfer files between systems (*Безопаснося передача файлов между системаи*)

### Configure local storage (*Настройка локального хранилища*)

- List, create, delete partitions on MBR and GPT disks (*Просмор, создание и уаление разделов на MBR и GPT дискаъ*)
- Create and remove physical volumes (*Создание и удаление физических томов*)
- Assign physical volumes to volume groups (*Назначение физических томов в группы томов*)
- Create and delete logical volumes (*Создание и удаление логических томов*)
- Configure systems to mount file systems at boot by universally unique ID (UUID) or label (*Настройка систем для монтирования файловых систем при загрузуке с помолщью универсального уникального идентификатора или метки*)
- Add new partitions and logical volumes, and swap to a system non-destructively (*Добавление новых разделов, логичесих томов и файла подкачки в систему без ее повреждения*)

### Create and configure file systems (*Создание и настрйока файловых систем*)

- Create, mount, unmount, and use vfat, ext4, and xfs file systems (*Создание, монтирование,размонтировани и использование файловых систем vfat, ext4 и xfs*)
- Mount and unmount network file systems using NFS (*Монтирование и размонтирование сетевых файловых систем используя NFS*)
- Configure autofs (*Настройка autofs*)
- Extend existing logical volumes (*Расширение существующего логического тома*)
- Create and configure set-GID directories for collaboration (*Создание и конфигурирование set-GID директорий для совместного использования*)
- Diagnose and correct file permission problems (*Диагностика и устранение проблем с разрешениями доступа к файлам*)

### Deploy, configure, and maintain systems (*Развертывание, настройка и обслуживание систем*)

- Schedule tasks using at and cron (*Планирование задач используя at и cron*)
- Start and stop services and configure services to start automatically at boot (*Запуск и остановка служб и настрйока автоматического запуска служб при загрузке системы*)
- Configure systems to boot into a specific target automatically (*Настрйока систем для загрузки в специальном режиме*)
- Configure time service clients (*Настройка клиента службы времени*)
- Install and update software packages from Red Hat Network, a remote repository, or from the local file system (*Установка и обновление пакето из Red Hat Network, удаленного репозитория или из локальной файловой системы*)
- Modify the system bootloader (*Изменение системного загрузчика*)

### Manage basic networking (*Основы настройки сетей*)

- Configure IPv4 and IPv6 addresses (*Настройка IPv4 и IPv6 адресов*)
- Configure hostname resolution (*Настройка разрешения имени хоста*)
- Configure network services to start automatically at boot (*Настрйока сетевых служб для атовматического запуска при загрузке*)
- Restrict network access using firewall-cmd/firewall (*Ограничение сетевого доступа используя firewall-cmd/firewall *)

### Manage users and groups (*Управление пользователями и группами*)

- Create, delete, and modify local user accounts (*Создание, удаление и изменение локальных пользовательских учетных записей*)
- Change passwords and adjust password aging for local user accounts (*Изменение паролей и регулирование срока действия паролья для локального пользователя*)
- Create, delete, and modify local groups and group memberships (*Создание, удалене и изменение локальных пользовательских групп и членства в группе*)
- Configure superuser access (*Настройка доступа суперпользователя*)

### Manage security (*Настройка безопасности*)

- Configure firewall settings using firewall-cmd/firewalld (*Настройка фаервола используя firewall-cmd/firewalld*)
- Manage default file permissions (*Настройка разрешений файла*)
- Configure key-based authentication for SSH (*Настрйока аутентифкации для SSH на основе ключей*)
- Set enforcing and permissive modes for SELinux (*???Настройка принудительного и разрешающего режимов для SELinux*)
- List and identify SELinux file and process context (*Просмотр и идентификация ???*)
- Restore default file contexts (*Восстановление контекста файлов поумолчанию*)
- Manage SELinux port labels (*Управление метками портов SELinux*)
- Use boolean settings to modify system SELinux settings (*Использование булевых переменныех для изменения настроек SELinux*)
- Diagnose and address routine SELinux policy violations (*Диагностика и устраненние обучных нарушений политики SELinux*)

### Manage containers

- Find and retrieve container images from a remote registry (*Поиск и получение образов контейнеров из удаленного хранилища*)
- Inspect container images (*Инспекция контейеров*)
- Perform container management using commands such as podman and skopeo (*Управление контейнерами с помощщью podman и skopeo*)
- Build a container from a Containerfile (*Сборка контейнера из манифеста*)
- Perform basic container management such as running, starting, stopping, and listing running containers (*???Базовые операции с контейнером: зпуск, остановка, просмотр запущеных контейнеров*)
- Run a service inside a container (*Запуск службы внутри контейнера*)
- Configure a container to start automatically as a systemd service (*НАстройка автоматического запуска контейнера как службы systemd*)
- Attach persistent storage to a container (*Монтирование постоянного хранилаща в контейнер*)

### Примечанние 

As with all Red Hat performance-based exams, configurations must persist after reboot without intervention.

Red Hat reserves the right to add, modify, and remove objectives. Such changes will be made public in advance through revisions to this document.