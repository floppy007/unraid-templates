# Unraid Templates

> **[Deutsch](#deutsch)** | **[English](#english)**

---

<a id="deutsch"></a>

## Deutsch

Unraid Docker-Templates für meine Self-Hosted Apps.

### Verfügbare Apps

| App | Beschreibung | Docker Hub |
|---|---|---|
| [TaskFlow](apps/taskflow.xml) | Projekt- & Aufgabenverwaltung (Kanban, Drag & Drop, LDAP) | [floppy001/taskflow](https://hub.docker.com/r/floppy001/taskflow) |
| [WebDash](apps/webdash.xml) | Leichtgewichtiges Server-Dashboard mit Docker-Erkennung | [floppy001/webdash](https://hub.docker.com/r/floppy001/webdash) |

### Installation

**Option 1: Template Repository hinzufügen**

1. Unraid WebUI → **Docker** → **Template Repositories**
2. URL einfügen:
   ```
   https://github.com/floppy007/unraid-templates
   ```
3. **Save** klicken
4. Unter **Add Container** die gewünschte App auswählen

**Option 2: Einzelnes Template manuell installieren**

```bash
# TaskFlow
curl -Lo /boot/config/plugins/dockerMan/templates-user/my-taskflow.xml https://raw.githubusercontent.com/floppy007/unraid-templates/master/apps/taskflow.xml

# WebDash
curl -Lo /boot/config/plugins/dockerMan/templates-user/my-webdash.xml https://raw.githubusercontent.com/floppy007/unraid-templates/master/apps/webdash.xml
```

Danach unter **Docker** → **Add Container** die App auswählen.

---

<a id="english"></a>

## English

Unraid Docker templates for my self-hosted apps.

### Available Apps

| App | Description | Docker Hub |
|---|---|---|
| [TaskFlow](apps/taskflow.xml) | Project & task management (Kanban, drag & drop, LDAP) | [floppy001/taskflow](https://hub.docker.com/r/floppy001/taskflow) |
| [WebDash](apps/webdash.xml) | Lightweight server dashboard with Docker discovery | [floppy001/webdash](https://hub.docker.com/r/floppy001/webdash) |

### Installation

**Option 1: Add Template Repository**

1. Unraid WebUI → **Docker** → **Template Repositories**
2. Add URL:
   ```
   https://github.com/floppy007/unraid-templates
   ```
3. Click **Save**
4. Go to **Add Container** and select the desired app

**Option 2: Install Single Template Manually**

```bash
# TaskFlow
curl -Lo /boot/config/plugins/dockerMan/templates-user/my-taskflow.xml https://raw.githubusercontent.com/floppy007/unraid-templates/master/apps/taskflow.xml

# WebDash
curl -Lo /boot/config/plugins/dockerMan/templates-user/my-webdash.xml https://raw.githubusercontent.com/floppy007/unraid-templates/master/apps/webdash.xml
```

Then go to **Docker** → **Add Container** and select the app.
