Haa. Waxaan ka soo saaray **qodobada ugu muhiimsan** ee Chapter 1, si aad ugu fududaato inaad barato ama imtixaan ugu diyaar garowdo. 

## 📚 Chapter 1: Introduction to Visual C#

### 1. Objects

* **Object** waa qayb ka mid ah program-ka oo kaydisa xog isla markaana qabata hawlo.
* Object wuxuu leeyahay:

  * **Properties** → xogta/astaamaha object-ka.
  * **Methods** → hawlaha object-ku qaban karo. 

### 2. Controls

**Controls** waa objects-ka ka muuqda GUI-ga program-ka.

Tusaalooyin:

* **Label**
* **Button**
* **TextBox**

Waxaa kaloo jira controls aan si toos ah uga muuqan GUI-ga, sida **Timer** iyo **OpenFileDialog**. 

### 3. .NET

**.NET** waa ururin classes iyo code ah oo loo isticmaalo samaynta programs, gaar ahaan Windows applications. Controls-ka waxaa lagu qeexaa classes gaar ah oo .NET bixiso. 

### 4. Visual Studio

**Visual Studio** waa **IDE (Integrated Development Environment)** oo lagu sameeyo laguna maamulo applications.

Qaybaha muhiimka ah:

* **Designer Window**
* **Solution Explorer**
* **Properties Window**
* **Toolbox**
* **Code Editor** 

### 5. Toolbox

**Toolbox** waa meesha aad ka dooranayso controls-ka aad ku dari lahayd application-ka.

Tusaale:

* Button
* CheckBox
* ComboBox
* Label
* ListBox
* TextBox 

### 6. Project iyo Solution

Tani waa **mid aad muhiim u ah**:

* **Project** = hal application.
* **Solution** = container qaadi kara hal ama dhowr project.
* **Project files** = files-ka code-ka iyo resources-ka application-ka. 

### 7. Form

Marka aad bilowdo Windows Forms App cusub, **Form1** ayaa si automatic ah loo abuuraa.

Form-ka waxaad:

* beddeli kartaa size-kiisa,
* ku dari kartaa controls,
* beddeli kartaa properties-kiisa. 

### 8. Properties

**Properties** waxay go'aamiyaan sida object-ku **u ekaanayo iyo sida uu u dhaqmo**.

Tusaale:

* `Text`
* `Name`
* `Font`
* `Size`
* `Visible`

Properties Window wuxuu leeyahay:

* **Left column** → magaca property-ga
* **Right column** → value-ga property-ga. 

### 9. Naming Controls

Magaca control-ka waxaa loo isticmaalaa code-ka.

Rules:

* Waa inuu ku bilaabmaa **letter** ama `_`
* Ma lahaan karo **spaces**
* Waxaa la isticmaali karaa letters, numbers iyo `_`

Tusaale sax ah:

```text
showDayButton
DisplayTotal
_ScoreLabel
```

Waxaa badanaa la isticmaalaa **camelCase**. 

### 10. C# Code Organization

C# code waxaa ugu muhiimsan:

**Namespace → Class → Method**

* **Namespace** = container haya classes.
* **Class** = container haya methods.
* **Method** = statements sameeya hawl gaar ah.
* **Source code file** = file-ka ay ku jiraan program statements. 

### 11. Important C# Files

Marka project cusub la sameeyo waxaa muhiim ah:

* **Program.cs** → wuxuu ka kooban yahay startup code.
* **Form1.cs** → code-ka la xiriira Form1. 

### 12. Event-Driven Programming ⭐

GUI applications waa **event-driven**.

Taasi waxay ka dhigan tahay program-ku inuu sugo user-ku inuu sameeyo wax sida:

* Button click
* Key press
* Mouse movement

Kadib program-ku wuxuu sameeyaa response.

**Event Handler** = method-ka shaqeeya marka event gaar ah dhaco. 

### 13. MessageBox

`MessageBox.Show()` waxaa loo isticmaalaa in fariin lagu soo bandhigo.

```csharp
MessageBox.Show("Hello World");
```

Marka button la riixo, fariintan ayaa soo baxaysa. 

### 14. Label Control

**Label** wuxuu ku soo bandhigaa text gudaha form-ka.

Properties muhiim ah:

* `Text`
* `Name`
* `Font`
* `BorderStyle`
* `AutoSize`
* `TextAlign` 

### 15. Assignment Operator `=`

`=` waxaa loo isticmaalaa in value lagu assignment-gareeyo variable ama property.

Tusaale:

```csharp
answerLabel.Text = "";
```

Tani waxay ka dhigaysaa Text-ka Label-ka mid madhan. 

### 16. IntelliSense ⭐

**IntelliSense** waa feature-ka Visual Studio ee kuu soo jeediya code markaad wax qorayso.

Waxay kuu soo jeedin kartaa:

* Keywords
* Variables
* Methods
* Classes
* Properties 

### 17. PictureBox

**PictureBox** waxaa loo isticmaalaa in sawir lagu soo bandhigo Form-ka.

Properties muhiim ah:

* `Image`
* `SizeMode`
* `Visible` 

### 18. Sequential Execution

Statements-ka program-ku waxay u shaqeeyaan **sida ay u kala horreeyaan**.

Sidaa darteed order-ka code-ku waa muhiim. Haddii order-ku khaldan yahay, waxaa dhici karta **logic error**. 

### 19. Comments

**Comments** waa qoraallo lagu sharaxo code-ka, waxaana compiler-ku uusan u tixgelin code ahaan.

Single-line:

```csharp
// This is a comment
```

Multi-line:

```csharp
/*
   This is a
   block comment
*/
```



### 20. `this.Close()` iyo `Application.Exit()`

Kuwani waa **aad muhiim u ah imtixaanka**:

```csharp
this.Close();
```

→ wuxuu xirayaa **current form**.

```csharp
Application.Exit();
```

→ wuxuu xirayaa **application-ka oo dhan**. 

### 21. Syntax Errors

Visual Studio wuxuu baarayaa syntax errors markaad code qorayso.

Haddii error jiro, badanaa waxaa lagu calaamadeeyaa **red jagged underline**. 

---
