# ສາລະບານ

- ບົດນຳ

- ບົດທີ 0 Blink

- ບົດທີ 1 Experiment Blink

- ບົດທີ 2 Switch

- ບົດທີ 3 RGB

- ບົດທີ 4 Buzzer

- ບົດທີ 5 Potentiometer

- ບົດທີ 6 Relay

- ບົດທີ 7 Servo

- ບົດທີ 8 Seven Segment

- ບົດທີ 9 Color Matching Sound Alarm System

- ບົດທີ 10 See Battery with LED and Seven Segment

# ບົດນຳ

ໄມໂຄຣໂປຣເຊສເຊີ ແລະ ໄມໂຄຄອມພີວເຕີ ເປັນອົງປະກອບທີ່ສຳຄັນໃນຄອມພິວເຕີສະໄໝໃໝ່. ລະບົບອັດຕະໂນມັດ ແລະລະບົບຝັງຕົວ. ໄມໂຄຣໂປຣເຊສເຊີ (microprocessor) ເຮັດຫນ້າທີ່ເປັນຫນ່ວຍປະມວນຜົນກາງ (CPU) ທີ່ປະຕິບັດຄໍາສັ່ງ ແລະ ຄວບຄຸມການເຮັດວຽກຕ່າງໆ. ໄມໂຄຄອມພີວເຕີ (microcomputer) ແມ່ນການປະສົມປະສານຂອງ microprocessor ກັບຫນ່ວຍຄວາມຈໍາ ແລະ ອຸປະກອນເສີມເພື່ອເຮັດໃຫ້ມັນປະຕິບັດຫນ້າວຽກສະເພາະໃດຫນຶ່ງປະສິດທິພາບ.

ບົດ​ລາຍ​ງານ​ນີ້​ໄດ້ສຳຫຼວດການ​ທົດ​ລອງ​ທີ່​ສໍາ​ຄັນ​ທີ່​ສະ​ແດງ​ໃຫ້​ເຫັນ​ເຖິງການ​ເຮັດວຽກ​ພື້ນ​ຖານ​ຂອງ microcontroller ໄດ້​. ລວມມີການຄວບຄຸມການປ້ອນຂໍ້ມູນ/ການສົ່ງອອກແບບດິຈິຕອນ. ການເຊື່ອມຕໍ່ເຊັນເຊີ ແລະ ການສື່ສານກັບອຸປະກອນຕ່າງໆ. ການທົດລອງເຫຼົ່ານີ້ນໍາສະເໜີການໃຊ້ງານຕົວຈິງທີ່ຊ່ວຍໃຫ້ເຂົ້າໃຈການເຮັດວຽກ ແລະ ການປະຍຸກໃຊ້ຂອງ microcontrollers ໃນສະຖານະການຈິງ.

ຫຼັງຈາກຜ່ານການທົດສອບເຫຼົ່ານີ້, ນັກສຶກສາຈະໄດ້ຮັບປະສົບການທາງດ້ານປະຕິບັດຕົວຈິງໃນການເຊື່ອມຕໍ່ໄມໂຄຣຄອນໂທຣອນເລີກັບອຸປະກອນຕ່າງໆ, ການນຳໃຊ້ເຊັນເຊີ ແລະ ການພັດທະນາໂປຣແກຣມ, ເຊິ່ງເປັນພື້ນຖານສຳຄັນໃນການອອກແບບ ແລະ ພັດທະນາລະບົບທີ່ຊັບຊ້ອນຂຶ້ນໃນອະນາຄົດ.

# ບົດທີ 0 Blink

### 1\. ບົດນໍາ

ໂປຣແກຣມ **Blink** ແມ່ນໜຶ່ງໃນໂປຣແກຣມພື້ນຖານຂອງ **Arduino** ທີ່ໃຊ້ສໍາລັບທົດສອບການເຮັດວຽກຂອງບອດ. ຈຸດປະສົງຄື ທໍາໃຫ້ **LED** ທີ່ຢູ່ໃນບອດ (ຫລື LED ພາຍນອກ) ກະພິບເປັນຈັງຫວະ. ນີ້ແມ່ນຄືການຝຶກຄວບຄຸມຂາອອກ **(Output)** ຂອງ **Arduino** ໂດຍຜ່ານຄໍາສັ່ງ digitalWrite() ແລະ delay().

### 2\. ອຸປະກອນທີ່ໃຊ້

- ບອດ **Arduino** (ສະເພາະ **Arduino Uno, Mega, Nano** ຫລືລຸ່ນອື່ນ)
- **LED** (ທີ່ມີໃນບອດ ຫລືຂຽນເພີ່ມພາຍນອກ)
- ສາຍ **USB** ສໍາລັບເຊື່ອມຕໍ່ກັບຄອມພິວເຕີ
- ໂປຣແກຣມ **Arduino IDE** ສໍາລັບຂຽນແລະອັບໂຫລດໂປຣແກຣມ
### 3. ການເຊື່ອມຕໍ່ວົງຈອນ
- LED: ໃຊ້ໄຟ LED ໃນຕົວຢູ່ pin 13 ຂອງ Arduino.
- ການສະຫນອງພະລັງງານ: Arduino ສະຫນອງພະລັງງານໃຫ້ກັບວົງຈອນທັງຫມົດ.

![image](https://github.com/user-attachments/assets/7570daf5-86b3-4a02-bc53-e56e961db986)
![image](https://github.com/user-attachments/assets/d9142309-e9f5-4b0a-b33d-5f1906f77a30)


### 4\. ໂຄ້ດໂປຣແກຣມ Blink
<img width="253" alt="image" src="https://github.com/user-attachments/assets/055958cb-234f-4fdb-9f76-aa4b98f2b1b1" />




### 5\. ຫຼັກການເຮັດວຽກ

- ໂປຣແກຣມຈະສັບສະຫຼັບສະຖານະຂອງ **LED** ທຸກ **1 ວິນາທີ** ກໍ່ໃຫ້ເກີດຜົນກະພິບ
- ໃຊ້ຟັງຊັນ delay(1000); ສໍາລັບຄວບຄຸມເວລາໃນການເປີດ-ປິດ LED
- ໃຊ້ຄ່າຄົງທີ່ **LED_BUILTIN** ທໍາໃຫ້ສາມາດໃຊ້ງານໄດ້ກັບບອດ **Arduino** ທຸກລຸ່ນໄດ້ງ່າຍ

### 6\. ສະຫຼຸບ

ໂປຣແກຣມ **Blink** ແມ່ນໂປຣແກຣມພື້ນຖານໃນການຮຽນຮູ້ **Arduino** ຊ່ວຍໃຫ້ເຂົ້າໃຈການຄວບຄຸມຂາ **Output** ແລະ ການຄວບຄຸມເວລາ, ຊຶ່ງເປັນພື້ນຖານສໍາຄັນສໍາລັບການພັດທະນາໂປຣເຈັກ Arduino ຕໍ່ໄປ.

# ບົດທີ 1 Experiment Blink

### 1\. ບົດນໍາ

ການທົດສອບ **Blink** ແມ່ນການຮຽນຮູ້ພື້ນຖານຂອງ **Arduino** ທີ່ໃຊ້ເພື່ອທົດສອບການເຮັດວຽກຂອງຂາ **Output** ໂດຍໃຊ້ **LED** ທີ່ມີຢູ່ໃນບອດ **(LED_BUILTIN)** ໃຫ້ມັນກະພິບເປັນຈັງຫວະ. ການທົດສອບນີ້ຈະຊ່ວຍໃຫ້ເຂົ້າໃຈການໃຊ້ຄໍາສັ່ງ **digitalWrite()**, **delay()** ແລະ ຫຼັກການເຮັດວຽກຂອງ **loop()** ທີ່ທຳງານຊ້ໍາໆຢ່າງອັດຕະໂນມັດ.

### 2\. ອຸປະກອນທີ່ໃຊ້

- ບອດ **Arduino** (ສາມາດໃຊ້ Arduino Uno, Mega, Nano)
- **LED** (ໃຊ້ LED ທີ່ຢູ່ໃນບອດ, ຂາ 13)
- ສາຍ **USB** ສໍາລັບເຊື່ອມຕໍ່ຄອມພິວເຕີ
- ໂປຣແກຣມ **Arduino IDE** ສໍາລັບຂຽນແລະອັບໂຫລດໂປຣແກຣມ

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

LED ແມ່ນເຊື່ອມຕໍ່ກັບ pin output ໂດຍຜ່ານຕົວຕ້ານທານ. ດ້ວຍຂາລົບທີ່ເຊື່ອມຕໍ່ກັບ GND, Microcontroller Arduino ຈະປ່ຽນສະຖານະຂອງ output ເພື່ອເຮັດໃຫ້ໄຟ LED ກະພິບ.
<img width="185" alt="image" src="https://github.com/user-attachments/assets/f7da1fcf-7625-4bdc-add8-32d9b99bf695" />
<img width="145" alt="image" src="https://github.com/user-attachments/assets/a8dec270-9cea-4105-848b-831533dfa73d" />

### 4\. ໂຄ້ດໂປຣແກຣມ Blink
<img width="267" alt="image" src="https://github.com/user-attachments/assets/7c872a9f-5b48-4e28-a04a-5dd395765664" />


### 5\. ຫຼັກການເຮັດວຽກຂອງການທົດສອບ

- ສະຖານະຂອງ **LED** ຈະສັບສະຫຼັບໃນທຸກ **1 ວິນາທີ**
- ຄໍາສັ່ງ delay(1000); ຖືກໃຊ້ເພື່ອຄວບຄຸມເວລາໃນການເປີດ-ປິດ LED
- ຂອງຄໍາສັ່ງທີ່ຢູ່ໃນ loop() ຈະຖືກທຳວຽກຊ້ຳໄປເລື້ອຍໆ

### 6\. ສະຫຼຸບຜົນການທົດສອບ**

ການທົດສອບ **Blink** ຊ່ວຍໃຫ້ເຂົ້າໃຈວິທີການຄວບຄຸມຂາ **Output** ຂອງ **Arduino** ຜ່ານຄໍາສັ່ງ digitalWrite() ແລະ delay(). ນີ້ເປັນພື້ນຖານທີ່ສໍາຄັນສໍາລັບຄວາມເຂົ້າໃຈໃນການຄວບຄຸມອຸປະກອນອື່ນໆ ທີ່ມີຂາອອກ **(Output)** ຕໍ່ໄປ.

# ບົດທີ 2 Switch

### 1\. ບົດນຳ

ການທົດສອບນີ້ແມ່ນການໃຊ້ **Switch** (ປຸ່ມກົດ) ຄວບຄຸມການເປີດ-ປິດ **LED** ທີ່ຢູ່ໃນບອດ **Arduino** ໂດຍໃຊ້ຄໍາສັ່ງ **digitalRead()** ສໍາລັບອ່ານຄ່າຈາກປຸ່ມ ແລະ **digitalWrite()** ສໍາລັບຄວບຄຸມ **LED.**

### 2\. ອຸປະກອນທີ່ໃຊ້

- ບອດ **Arduino** (Uno, Mega, Nano ແລະລຸ້ນອື່ນໆ)
- **Push Button** (ປຸ່ມກົດ)
- ຕົວຕ້ານທານ **10kΩ** (Pull-down Resistor)
- **LED** (ໃຊ້ LED_BUILTIN ຫລື LED ຂ້າງນອກ)
- ສາຍ **Jumper**
- ໂປຣແກຣມ **Arduino IDE

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

- ປຸ່ມກົດແມ່ນເຊື່ອມຕໍ່ກັບ pin 2 (ການປ້ອນຂໍ້ມູນດິຈິຕອນ) ຂອງ **Arduino.**
- ຂາຫນຶ່ງຂອງປຸ່ມກົດແມ່ນເຊື່ອມຕໍ່ກັບ GND ແລະ ຂາອື່ນແມ່ນເຊື່ອມຕໍ່ກັບ pin 2.
- **LED** ແມ່ນເຊື່ອມຕໍ່ກັບ pin **LED** ໃນຕົວ (ຫຼື pin ດິຈິຕອນອື່ນ) ຜ່ານຕົວຕ້ານທານ. ຂາລົບແມ່ນເຊື່ອມຕໍ່ກັບ GND.
<img width="239" alt="image" src="https://github.com/user-attachments/assets/02721fa6-7764-4860-bc8f-e12c7c3266d7" />
<img width="114" alt="image" src="https://github.com/user-attachments/assets/867c7dae-1ed7-4f85-9a8f-4b6810c8c0df" />

### 4\. ໂຄ້ດ
```
int buttonState = 0; // ປ່ຽນແປງເກັບຄ່າສະຖານະຂອງປຸ່ມ

void setup()
{

    pinMode(2, INPUT); // ກຳນົດຂາ 2 ເປັນ Input ສໍາລັບປຸ່ມກົດ

    pinMode(LED_BUILTIN, OUTPUT); // ກຳນົດຂາ LED_BUILTIN ເປັນ Output

    Serial.begin(9600); // ເປີດການສື່ສານຜ່ານ Serial Monitor
}

void loop()
{

    buttonState = digitalRead(2); // ອ່ານຄ່າສະຖານະຂອງປຸ່ມ

    if (buttonState == HIGH)
    { // ຖ້າປຸ່ມຖືກກົດ

        Serial.println("Button HIGH"); // ສະແດງຜົນໃນ Serial Monitor

        digitalWrite(LED_BUILTIN, HIGH); // ເປີດ LED
    }
    else
    { // ຖ້າປຸ່ມບໍ່ໄດ້ກົດ

        Serial.println("Button LOW");

        digitalWrite(LED_BUILTIN, LOW); // ປິດ LED
    }

    delay(10); // ໜ່ວງເວລາໃຫ້ການອ່ານຄ່າຖືກຕ້ອງຂຶ້ນ
}
```
### 5\. ຜົນການທົດສອບ

- ກົດປຸ່ມ LED_BUILTIN ຈະເປີດ
- ປ່ອນປຸ່ມ LED_BUILTIN ຈະປິດ
- Serial Monitor ຈະສະແດງ "Button HIGH" ຫລື "Button LOW" ຕາມສະຖານະຂອງປຸ່ມ

### 6\. ສະຫຼຸບຜົນການທົດສອບ

ຈາກການທົດສອບ ພົບວ່າ **Arduino** ສາມາດອ່ານສະຖານະຂອງປຸ່ມກົດໄດ້ຖືກຕ້ອງ ຜ່ານ **digitalRead()** ແລະສາມາດໃຊ້ digitalWrite() ຄວບຄຸມ **LED** ໄດ້ຢ່າງແມ່ນຍໍາ.

# ບົດທີ 3 RGB

### 1\. ບົດນຳ

ໃນໂຄງງານນີ້, ພວກເຮົາຈະໃຊ້ **Arduino** ສຳລັບຄວບຄຸມ **RGB LED** ຜ່ານຄຳສັ່ງຈາກ **Serial Monitor**. RGB LED ສາມາດເປີດໃຫ້ເກີດສີທີ່ຕ້ອງການ ໂດຍໃຊ້ສີພື້ນຖານ 3 ສີ: **ແດງ (Red), ຂຽວ (Green), ຟ້າ (Blue)**, ຫຼື ຜະສົມສີໃຫ້ເກີດສີຕ່າງໆ.

ໂຄດທີ່ໃຊ້ສາມາດ **ເປີດ-ປິດ** RGB LED ໂດຍປ້ອນຄຳສັ່ງໃນ Serial Monitor ຢ່າງ "on", "off", "r", "g", "b", "rg", "rb", "gb". ນອກນີ້ຍັງມີຟັງຊັນ allColors() ທີ່ໃຫ້ LED ກະພິບສີຕ່າງໆ ຕາມລຳດັບ.

### 2\. ອຸປະກອນທີ່ໃຊ້

1. **Arduino Uno/Nano/Mega** (ໃຊ້ຕາມຄວາມເໝາະສົມ)
2. **RGB LED (Common Cathode ຫຼື Common Anode)**
3. **ຕົວຕ້ານທານ 220Ω - 330Ω** (ຄວບຄຸມກະແສໄຟ)
4. **ສາຍ Jumper**
5. **ຄອມພິວເຕີທີ່ຕິດຕັ້ງ Arduino IDE**

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

RGB LED ມີ 4 pins ຄື: pin ສໍາລັບແຕ່ລະສີ (ສີແດງ, ສີຂຽວ, ສີຟ້າ) ແລະ pin ສໍາລັບດິນ (ສໍາລັບ Common Cathode) ຫຼື VCC (ສໍາລັບ Common Anode), ແຕ່ລະສີແມ່ນເຊື່ອມຕໍ່ກັບ pin ດິຈິຕອລຂອງ Arduino ໂດຍໃຊ້ຕົວຕ້ານທານໃນວົງຈອນ
<img width="215" alt="image" src="https://github.com/user-attachments/assets/a956d7b5-5e29-4baa-b733-70cce0376079" />
<img width="140" alt="image" src="https://github.com/user-attachments/assets/e8c44872-0e0b-4f4a-b01d-7507d3e29037" />

### 4\. ໂຄ້ດ
```

int ledPins\[\] = {11, 10, 9};

void setup()
{

    // put your setup code here, to run once:

    Serial.begin(9600);

    for (int pin : ledPins)
    {

        pinMode(pin, OUTPUT);
    }

    // exercise

    // change foreach to for loop
}

void loop()
{

    // put your main code here, to run repeatedly:

    while (Serial.available() > 0)
    {

        // read input from serial monitor

        String input = Serial.readStringUntil('\\n'); // Read until newline

        for (int pin : ledPins)
        {

            digitalWrite(pin, LOW);
        }

        delay(10);

        if (input == "on" or input == "rgb" or input == "rbg" or input == "grb" or input == "gbr" or input == "brg" or input == "bgr")
        {

            // turn all LEDs on

            for (int pin : ledPins)
            {

                digitalWrite(pin, HIGH);
            }
        }

        else if (input == "off")
        {

            // turn all LEDs off

            for (int pin : ledPins)
            {

                digitalWrite(pin, LOW);
            }
        }

        else if (input == "r")
        {

            digitalWrite(ledPins\[0\], HIGH);
        }

        else if (input == "g")
        {

            digitalWrite(ledPins\[1\], HIGH);
        }

        else if (input == "b")
        {

            digitalWrite(ledPins\[2\], HIGH);
        }

        else if (input == "rg" or input == "gr")
        {

            digitalWrite(ledPins\[0\], HIGH);

            digitalWrite(ledPins\[1\], HIGH);
        }

        else if (input == "rb" or input == "br")
        {

            digitalWrite(ledPins\[0\], HIGH);

            digitalWrite(ledPins\[2\], HIGH);
        }

        else if (input == "gb" or input == "bg")
        {

            digitalWrite(ledPins\[1\], HIGH);

            digitalWrite(ledPins\[2\], HIGH);
        }

        else
        {

            allColors();
        }
    }
}

void allColors()
{

    // WHITE

    for (int pin : ledPins)
    {

        digitalWrite(pin, HIGH);
    }

    delay(100);

    for (int pin : ledPins)
    {

        digitalWrite(pin, LOW);
    }

    delay(100);

    // RED, GREEN, BLUE

    for (int pin : ledPins)
    {

        digitalWrite(pin, HIGH);

        delay(100);

        digitalWrite(pin, LOW);

        delay(100);
    }

    // RED + GREEN index 0 and index 1

    for (int i = 0; i < 2; i++)
    {

        digitalWrite(ledPins\[i\], HIGH);
    }

    delay(100);

    for (int i = 0; i < 2; i++)
    {

        digitalWrite(ledPins\[i\], LOW);
    }

    delay(100);

    // RED BLUE index 0 and index 2

    for (int i = 0; i < 3; i += 2)
    {

        digitalWrite(ledPins\[i\], HIGH);
    }

    delay(100);

    for (int i = 0; i < 3; i += 2)
    {

        digitalWrite(ledPins\[i\], LOW);
    }

    delay(100);

    // GREEN + BLUE index 1 and index 2

    for (int i = 1; i < 3; i++)
    {

        digitalWrite(ledPins\[i\], HIGH);
    }

    delay(100);

    for (int i = 1; i < 3; i++)
    {

        digitalWrite(ledPins\[i\], LOW);
    }

    delay(100);
}
```
### 5\. ຜົນການທົດລອງ

1. ປ້ອນ "on" LED ຈະເປີດທັງ 3 ສີ
2. ປ້ອນ "off" LED ຈະດັບ
3. ປ້ອນ "r", "g", "b" LED ຈະເປີດເປັນສີນັ້ນ
4. ປ້ອນ "rg", "rb", "gb" LED ຈະເປີດສີຜະສົມ
5. ຖ້າປ້ອນຄຳສັ່ງທີ່ບໍ່ກຳນົດ LED ຈະກະພິບສີຕ່າງໆ.

### 6\. ສະຫຼຸບ

ໂຄງງານນີ້ ຊ່ວຍໃຫ້ເຂົ້າໃຈການເຮັດວຽກຂອງ **RGB LED** ແລະການຄວບຄຸມໂດຍ **Arduino** ຜ່ານ **Serial Monitor**. ສາມາດນຳໄປຂະຫຍາຍໃຫ້ສາມາດ **ປັບຄວາມສະຫວ່າງ (PWM)** ຫຼື **ໃຊ້ເຊັນເຊີໃນການປ່ຽນສີໂດຍອັດຕະໂນມັດ**.

# ບົດທີ 4 Buzzer

### 1\. ບົດນຳ

ໂຄງງານນີ້ເປັນການນຳ **Buzzer** ມາໃຊ້ໃນການສ້າງສຽງດົນຕີຜ່ານ **Arduino.** ໂປຣແກຣມຈະສ້າງທຳນອງດົນຕີໂດຍກຳນົດໂຕເລກຄວາມຖີ່ຂອງສຽງໃນຮູບແບບ **Hz** (Hertz) ໃຫ້ Buzz**er** ສຽງດັງຕາມໂນ໊ດທີ່ກຳນົດ.

ໃນໂຄດນີ້, ພວກເຮົາໄດ້ກຳນົດໂນ໊ດເພງທີ່ຈະຫຼິ້ນ ແລະ ລະດັບຄວາມຍາວຂອງແຕ່ລະໂນ໊ດ. **Arduino** ຈະໃຊ້ຄຳສັ່ງ **tone()** ໃນການໃຫ້ **Buzzer** ສ້າງສຽງ, ແລະຄຳສັ່ງ **noTone()** ໃນການປິດສຽງ.

### 2\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega (ໃຊ້ຕາມຄວາມເໝາະສົມ)
2. Buzzer (Active/Passive Buzzer)
3. ສາຍ Jumper
4. ຄອມພິວເຕີທີ່ຕິດຕັ້ງ Arduino IDE
### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

- ເຊື່ອມຕໍ່ pin buzzer ກັບ pin 9 ຂອງ Arduino.
- ເຊື່ອມຕໍ່ຂາອື່ນຂອງ buzzer ກັບ GND.
<img width="223" alt="image" src="https://github.com/user-attachments/assets/5d8ffbeb-953a-40e2-8c7d-b7443c2a5182" />
<img width="135" alt="image" src="https://github.com/user-attachments/assets/8991f136-070f-45d4-b24d-bae46f8804b4" />

### 4\. ໂຄດທີ່ໃຊ້
```
// Notes frequencies (in Hz) for different pitches

#define NOTE_C4 131

#define NOTE_D4 293

#define NOTE_E4 329

#define NOTE_F4 349

#define NOTE_G4 392

#define NOTE_A4 440

#define NOTE_B4 493

#define NOTE_C5 523

// Melody notes and durations

int melody\[\] = {

    NOTE_C4,
    NOTE_F4,
    NOTE_G4,
    NOTE_A4,

    NOTE_G4,
    NOTE_F4,
    NOTE_A4,
    NOTE_G4,

    NOTE_A4,
    NOTE_B4,
    NOTE_C5,
    NOTE_A4,

    NOTE_C5,
    NOTE_B4,
    NOTE_A4,
    NOTE_B4,

    NOTE_C5,
    NOTE_B4,
    NOTE_A4,
    NOTE_G4,

    NOTE_E4,
    NOTE_D4,
    NOTE_E4,
    NOTE_F4,

    NOTE_G4,
    NOTE_E4,
    NOTE_C4,
    NOTE_D4,

    NOTE_D4,
    NOTE_E4,
    NOTE_F4,
    NOTE_G4,

    NOTE_B4,

};

int noteDurations\[\] = {
    2, 2, 4, 2,

    2, 2, 4, 3,

    3, 3, 2, 3,

    3, 3, 3, 2,

    3, 3, 3, 2,

    3, 3, 3, 3,

    3, 3, 3, 2,

    2, 2, 2,

};

void setup()
{

    // No setup needed
}

void loop()
{

    // Play each note in the melody

    for (int i = 0; i < 200; i++)
    {

        int noteDuration = 1000 / noteDurations\[i\]; // Note duration in milliseconds

        tone(8, melody\[i\], noteDuration); // Play the note on pin 8

        delay(noteDuration \* 1.3); // Pause between notes

        noTone(8); // Stop the tone
    }

    delay(2000); // Pause before repeating the melody
}
```

### 5\. ການເຮັດວຽກຂອງວົງຈອນ
- ການຫຼິ້ນ Melody: ໃຊ້ຟັງຊັນ tone() ເພື່ອຫຼິ້ນໂນດທີ່ແຕກຕ່າງກັນຜ່ານ buzzer ທີ່ເຊື່ອມຕໍ່ກັບ pin 9 ຂອງ Arduino, ຄວາມຖີ່ຂອງໂນດແມ່ນຖືກກໍານົດຕາມພາລາມິເຕີທີ່ລະບຸ ແລະ ຄວາມຍາວຂອງໂນດແມ່ນຄວບຄຸມໂດຍຜ່ານ array noteDurations\[\].
- ການຢຸດສຽງ: ຟັງຊັນ noTone() ຖືກນໍາໃຊ້ເພື່ອຢຸດສຽງເມື່ອໂນດໄດ້ສໍາເລັດການຫຼິ້ນ ແລະ ຈະມີ(delay()) ເພື່ອໃຫ້ທຸກໆໂນດມີເວລາຢຸດທີ່ເຫມາະສົມ.

# ບົດທີ 5 Potentiometer

### 1\. ບົດນຳ

ໃນໂຄງງານນີ້, ພວກເຮົາຈະນຳ **Potentiometer** (ໂພເຕນຊີໂອເມັດເຕີ) ມາໃຊ້ໃນການຄວບຄຸມຄວາມສະຫວ່າງຂອງ **LED** ຜ່ານ **Arduino.**

Potentiometer ເປັນອຸປະກອນອິເລັກໂທຣນິກທີ່ໃຫ້ຄ່າແຮງຕິດຕໍ່ **(Resistance)** ປ່ຽນແປງໄດ້. ເມື່ອພວກເຮົາຫມູນ **Potentiometer**, ມັນຈະປ່ຽນໄຟສັນຍານອະນາລອກ **(Analog Signal)** ໃຫ້ **Arduino** ອ່ານຄ່າ, ແລ້ວນຳມາແປງໃຫ້ເປັນຄ່າດິຈິຕອນໃນການຄວບຄຸມຄວາມສະຫວ່າງຂອງ **LED.**

### 2\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega (ໃຊ້ຕາມຄວາມເໝາະສົມ)
2. Potentiometer 10kΩ
3. LED 1 ດວງ
4. ຕົວຕ້ານທານ (Resistor) 220Ω
5. ສາຍ Jumper
6. ຄອມພິວເຕີທີ່ຕິດຕັ້ງ Arduino IDE

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

- ເຊື່ອມຕໍ່ potentiometer ກັບ Arduino ດັ່ງຕໍ່ໄປນີ້:
- ຂາ potentiometer ຊ້າຍໄປຫາ 5V ໃນ Arduino.
- ຂາ potentiometer ຂວາໄປຫາ GND.
- pin ກາງ (wiper) ຂອງ potentiometer ແມ່ນເຊື່ອມຕໍ່ກັບ Analog A0 pin ຂອງ Arduino.
- ເຊື່ອມຕໍ່ LED ກັບ pin 11 ໃນ Arduino.
- ຂາຍາວ (Anode pin) ຂອງ LED ໄປກັບ pin 11.
- ຂາສັ້ນ (ຂາ Cathode) ຂອງ LED ໂດຍຜ່ານ 220Ω resistor ຕໍ່ກັບ GND.
<img width="167" alt="image" src="https://github.com/user-attachments/assets/6a90512f-1c86-4333-8937-bee439b23cb4" />
<img width="192" alt="image" src="https://github.com/user-attachments/assets/743a594e-dba4-4ddc-95ae-dd858238946e" />

### 4\. ໂຄ້ດ
```
int analogValue = 0; // ຄ່າອະນາລອກທີ່ອ່ານຈາກ Potentiometer

int ledValue = 0; // ຄ່າສຳລັບຄວບຄຸມຄວາມສະຫວ່າງ LED

void setup()
{

    Serial.begin(9600); // ເປີດ Serial Monitor ສຳລັບສະແດງຄ່າ

    pinMode(11, OUTPUT); // ກຳນົດ Pin 11 ໃຫ້ເປັນຂາອອກ
}

void loop()
{

    analogValue = analogRead(A0); // ອ່ານຄ່າໄຟຟ້າຈາກ Potentiometer

    Serial.println(analogValue); // ສົ່ງຄ່າທີ່ອ່ານໄປຫາ Serial Monitor

    // ແປງຄ່າອະນາລອກ (0-1023) ເປັນຄ່າ PWM (0-255)

    ledValue = map(analogValue, 0, 1023, 0, 255);

    Serial.println(ledValue); // ສົ່ງຄ່າທີ່ປັບໃຫ້ Serial Monitor

    analogWrite(11, ledValue); // ຄວບຄຸມຄວາມສະຫວ່າງຂອງ LED

    delay(10); // ດຶ່ງເວລາໃຫ້ການອ່ານຄ່າຖືກຕ້ອງຍິ່ງຂຶ້ນ
}
```
### 5\. ຜົນທີ່ໄດ້

ເມື່ອຫມູນ Potentiometer:

- ຫາ 5V → LED ຈະສະຫວ່າງສູງສຸດ
- ຫາ 0V → LED ຈະດັບ
- ຄ່າຄວາມສະຫວ່າງຈະປ່ຽນໄປຕາມລະດັບໄຟຟ້າທີ່ປ່ຽນໄປ

### 6\. ສະຫຼຸບ

ໂຄງງານນີ້ເປັນພື້ນຖານສຳລັບການໃຊ້ Potentiometer ກັບ Arduino ເພື່ອຄວບຄຸມອຸປະກອນຕ່າງໆ.

# ບົດທີ 6 Relay

### 1\. ບົດນຳ**

ໂຄງງານນີ້ເປັນການສາທິດການໃຊ້ **Relay** ກັບ **Arduino** ຜ່ານການໃຊ້ **LED_BUILTIN** ເປັນຕົວແທນການຄວບຄຸມ **Relay. Relay** ແມ່ນອຸປະກອນທີ່ໃຊ້ໃນການເປີດ/ປິດວົງຈອນໄຟຟ້າ ຜ່ານການຄວບຄຸມດ້ວຍສັນຍານດິຈິຕອນ.

### 2\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega
2. Relay Module 5V
3. LED (ສຳລັບທົດສອບ)
4. ສາຍ Jumper
5. ແຫຼ່ງຈ່າຍໄຟ (5V DC ຫລື 220V AC ຂື້ນກັບການນຳໃຊ້)

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

- ເຊື່ອມຕໍ່ Relay ກັບ Arduino.
- IN PIN (ສັນຍານຄວບຄຸມ) ຂອງ Relay → LED_BUILTIN pin (pin 13) ຂອງ Arduino.
- GND pin ຂອງ relay → GND ຂອງ Arduino
- VCC pin ຂອງ relay → 5V ຂອງ Arduino
- ເຊື່ອມຕໍ່ LED ກັບ relay ໄດ້.
- COM (ທົ່ວໄປ) pin ຂອງ relay →ເຊື່ອມຕໍ່ກັບ pole ບວກຂອງ LED ໄດ້.
- NO (ເປີດປົກກະຕິ) pin of relay → ເຊື່ອມຕໍ່ກັບ 5V ຂອງ Arduino.
- ຂົ້ວລົບຂອງ LED → 220Ω resistor → GND ຂອງ Arduino.
<img width="206" alt="image" src="https://github.com/user-attachments/assets/f08c6064-123a-40b4-89a1-0abcffd5ae34" />
<img width="224" alt="image" src="https://github.com/user-attachments/assets/eda03c0b-3fba-4c6c-954e-b0dc3d28f5eb" />

### 4\. ໂຄ້ດ
```
void setup()
{

    pinMode(LED_BUILTIN, OUTPUT); // ກຳນົດຂາອອກ (ຕົວແທນ Relay)
}

void loop()
{

    digitalWrite(LED_BUILTIN, HIGH); // ເປີດ Relay

    delay(1000); // ລໍຖ້າ 1 ວິນາທີ

    digitalWrite(LED_BUILTIN, LOW); // ປິດ Relay

    delay(1000); // ລໍຖ້າ 1 ວິນາທີ
}
```

### 5\. ຜົນທີ່ໄດ້

- Relay ຈະເປີດ 1 ວິນາທີ ແລ້ວປິດ 1 ວິນາທີ ຊ້ຳໆ
- ຖ້າ Relay ມີ LED ໃນຕົວ, ຂອງມັນຈະເປີດ/ປິດຄືກັນ
- ສາມາດນຳໃຊ້ Relay ຄວບຄຸມອຸປະກອນໄຟຟ້າໄດ້ໃນຄວາມແຮງສູງ

### 6\. ສະຫຼຸບ

ໂຄງງານນີ້ເປັນພື້ນຖານສຳລັບການໃຊ້ Relay ຄວບຄຸມອຸປະກອນຕ່າງໆ.

# ບົດທີ 7 Servo

### 1\. ບົດນຳ

ໂຄງງານນີ້ເປັນການສາທິດການໃຊ້ **Servo Motor** ໃນການຄວບຄຸມມຸມຫັນໂດຍໃຊ້ **Potentiometer** ປັບມຸມ. **Servo** ແມ່ນອຸປະກອນທີ່ສາມາດຄວບຄຸມມຸມຫັນໄດ້ຢ່າງແມ່ນຍຳ, ໃຊ້ວຽກຢູ່ໃນລະບົບອັດຕະໂນມັດ, ຫລື ຫຸ່ນຍົນ.

### 2\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega
2. Servo Motor (SG90 ຫລື MG995 ຂື້ນກັບການນຳໃຊ້)
3. Potentiometer 10KΩ
4. ສາຍ Jumper
5. ແຫຼ່ງຈ່າຍໄຟ (5V DC)

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

- ເຊື່ອມຕໍ່ຂາ VCC ຂອງ servo ກັບ 5V ໃນ Arduino.
- ເຊື່ອມຕໍ່ GND pin ຂອງ servo ກັບ GND ຂອງ Arduino.
- ເຊື່ອມຕໍ່ສາຍສັນຍານຂອງ servo ກັບ pin 9 ຂອງ Arduino.
- ເຊື່ອມຕໍ່ pin 1 ຂອງ potentiometer ກັບ 5V ໃນ Arduino.
- ເຊື່ອມຕໍ່ pin 2 (ກາງ) ຂອງ Potentiometer ກັບ A0 ຂອງ Arduino.
- ເຊື່ອມຕໍ່ pin 3 ຂອງ Potentiometer ກັບ GND ຂອງ Arduino.
<img width="174" alt="image" src="https://github.com/user-attachments/assets/ad527709-b227-4db3-973a-ae2bfc23a741" />
<img width="221" alt="image" src="https://github.com/user-attachments/assets/5dc38a5e-8029-4e93-9627-9d0d4f428184" />

### 4\. ໂຄ້ດ
```
#include <Servo.h>;

Servo myservo; // ສ້າງອອບເຈັກຄວບຄຸມ Servo

int potpin = A0; // ກຳນົດ Potentiometer ຢູ່ຂາ A0

int val; // ຕົວແປເກັບຄ່າອ່ານຈາກ Potentiometer

void setup()
{

    Serial.begin(9600); // ສົ່ງຄ່າຜ່ານ Serial Monitor

    myservo.attach(9); // ເຊື່ອມ Servo ກັບขา 9
}

void loop()
{

    val = analogRead(potpin); // ອ່ານຄ່າ Potentiometer (0 - 1023)

    Serial.print("pot = ");

    Serial.print(val);

    Serial.print(", servo = ");

    val = map(val, 0, 1023, 0, 180); // ປັບສະເກລເປັນ 0 - 180 ອົງສາ

    Serial.println(val);

    myservo.write(val); // ປັບມຸມ Servo

    delay(15); // ລໍຖ້າການເຄື່ອນໄຫວຂອງ Servo
}
```
### 5\. ຜົນທີ່ໄດ້

- ເມື່ອໝູນ Potentiometer → Servo ຈະຫັນມຸມຕາມຄ່າ 0 - 180°
- ເມື່ອຄິກ Serial Monitor → ຈະເຫັນຄ່າທີ່ຖືກອ່ານຈາກ Potentiometer ແລະ ມຸມຂອງ Servo
- Servo ຕອບສະໜອງໄວ ແລະ ເຄື່ອນໄຫວໄດ້ຢ່າງແມ່ນຍຳ

### 6\. ສະຫຼຸບ

ໂຄງງານນີ້ໄດ້ສາທິດວິທີຄວບຄຸມ Servo Motor ຜ່ານ Potentiometer ໃນ Arduino. ໃຊ້ໃນໂຄງງານເຊັ່ນ: ຫຸ່ນຍົນ

### ບົດທີ 8 Seven Segment

### 1\. ບົດນຳ

**Seven Segment Display (SSD)** ເປັນອຸປະກອນສຳລັບສະແດງຕົວເລກ **0-9** ທີ່ມັກໃຊ້ຢູ່ໃນ ປ້າຍສະແດງຂໍ້ມູນ, ໂມງດິຈິຕອນ, ແລະ ເຄື່ອງຊັ່ງນໍ້າໜັກ. ໃນໂຄງງານນີ້, ຈະໃຊ້ **Arduino** ຄວບຄຸມ **Seven Segment** ໃຫ້ນັບຂື້ນແລະນັບລົງ ຈາກ **0-9.**

### 2\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega
2. Seven Segment Display (ປະເພດ Common Cathode ຫລື Common Anode)
3. ສາຍ Jumper
4. ຕົວຕ້ານ 220Ω - 1KΩ (ຕໍ່ກັບ Seven Segment ເພື່ອຈຳກັດໄຟຟ້າ)

### 3\. ການເຊື່ອມຕໍ່ວົງຈອນ

ຈໍສະແດງຜົນ 7-Segment ມີ 7 pins (a-g) ເພື່ອສະແດງຕົວເລກ ແລະ common cathode (CC) ຫຼື common anode (CA) pin ເພື່ອກໍານົດປະເພດຂອງການດໍາເນີນງານ.

- ເຊື່ອມຕໍ່ pins a-g ຂອງ 7-Segment ກັບ Arduino pins: a → 2, b → 3, c → 4, d → 5, e → 6, f → 7, g → 8
- ເຊື່ອມຕໍ່ cathode ທົ່ວໄປ (CC) ຫຼື anode ທົ່ວໄປ (CA) pin ກັບ GND ຫຼື 5V ຕາມປະເພດຂອງ 7-Segment.
- ໃຊ້ຕົວຕ້ານທານ 220Ω ເປັນຊຸດກັບແຕ່ລະ pin a-g ເພື່ອຫຼຸດຜ່ອນກະແສໄຟຟ້າ.
<img width="209" alt="image" src="https://github.com/user-attachments/assets/42c115b4-2449-48de-b1bb-016677a20cc7" />
<img width="198" alt="image" src="https://github.com/user-attachments/assets/09858945-8181-4925-947e-d13064db4e3b" />

### 4\. ໂຄ້ດ
```
const int pins\[\] = {13, 12, 11, 10, 9, 8, 7, 6}; // ກຳນົດຂາສຳລັບ Seven Segment

const int digitStates\[10\]\[8\] = {

    {LOW, HIGH, HIGH, HIGH, HIGH, HIGH, HIGH, LOW}, // 0

    {LOW, LOW, LOW, HIGH, LOW, LOW, HIGH, LOW}, // 1

    {HIGH, LOW, HIGH, HIGH, HIGH, HIGH, LOW, LOW}, // 2

    {HIGH, LOW, HIGH, HIGH, LOW, HIGH, HIGH, LOW}, // 3

    {HIGH, HIGH, LOW, HIGH, LOW, LOW, HIGH, LOW}, // 4

    {HIGH, HIGH, HIGH, LOW, LOW, HIGH, HIGH, LOW}, // 5

    {HIGH, HIGH, HIGH, LOW, HIGH, HIGH, HIGH, LOW}, // 6

    {LOW, LOW, HIGH, HIGH, LOW, LOW, HIGH, LOW}, // 7

    {HIGH, HIGH, HIGH, HIGH, HIGH, HIGH, HIGH, LOW}, // 8

    {HIGH, HIGH, HIGH, HIGH, LOW, HIGH, HIGH, LOW} // 9

};

void setup()
{

    for (int i = 0; i < 8; i++)
        pinMode(pins\[i\], OUTPUT);
}

void displayDigit(int d)
{

    for (int i = 0; i < 8; i++)
        digitalWrite(pins\[i\], digitStates\[d\]\[i\]);
}

void clearDisplay()
{

    for (int i = 0; i < 8; i++)
        digitalWrite(pins\[i\], LOW);
}

void loop()
{

    for (int i = 0; i <= 9; i++)
    { // ນັບຂື້ນ 0-9

        displayDigit(i);

        delay(500);
    }

    clearDisplay();

    delay(500);

    for (int i = 9; i >= 0; i--)
    { // ນັບລົງ 9-0

        displayDigit(i);

        delay(500);
    }

    clearDisplay();

    delay(3000);
}
```
### 5\. ຜົນທີ່ໄດ້

- **Seven Segment Display** ຈະນັບຂື້ນຈາກ **0-9** ພັກ 500ms ແລ້ວນັບລົງຈາກ **9-0**
- ມີການດັບພັກ **500ms** ກ່ອນປ່ຽນຈາກນັບຂື້ນເປັນນັບລົງ
- ປ່ອນສັນຍານຖືກຕ້ອງຈຶ່ງສະແດງຕົວເລກໄດ້ແມ່ນຍຳ

### 6\. ສະຫຼຸບ

ໂຄງງານນີ້ໄດ້ສາທິດວິທີການນຳ **Seven Segment Display** ມານັບຂື້ນ/ນັບລົງ ຜ່ານ **Arduino.**

# Assignment Traffic light simulation

### 1\. ບົດນຳ

Traffic Light Simulation ແມ່ນໂຄງງານຈຳລອງສະຖານະສັນຍານໄຟຈລາຈອນ ທີ່ຄວບຄຸມດ້ວຍ Arduino. ໂຄງງານນີ້ຈະມີຄວາມສາມາດດັ່ງນີ້:

- ໄຟຈະລຽງລຳດັບໃນຮູບແບບ ແດງ → ຂຽວ → ເຫຼືອງ
- ມີ ປຸ່ມກົດ (Push Button) ເພື່ອກຳນົດໃຫ້ໄຟແດງເປີດທັນທີ່ ໃຊ້ໃນກໍລະນີ ຂ້າມຖະຫນົນ
- ມີ RGB LED ແລະ Buzzer ທີ່ຈະໄດ້ໃຊ້ໃນຂະນະທີ່ໄຟແດງເປີດ

### 2\. ຈຸດປະສົງ

- ຝຶກຂຽນໂຄດ Arduino ສຳລັບ ໄຟຈະລາຈອນ
- ສຶກສາການໃຊ້ Button, RGB LED, Buzzer
- ພັດທະນາ ລະບົບຈຳລອງສະຖານະການຂອງສັນຍານໄຟ

### 3\. ອຸປະກອນທີ່ໃຊ້

1. Arduino Uno/Nano/Mega
2. LED 3 ດວງ (ແດງ, ຂຽວ, ເຫຼືອງ) ສຳລັບໄຟຈະລາຈອນ
3. RGB LED ສຳລັບໄຟກະພິບໃນຂະນະທີ່ມີການກົດປຸ່ມ
4. Buzzer ສຳລັບສຽງແຈ້ງເຕືອນ
5. Push Button ສຳລັບກົດເພື່ອໃຫ້ໄຟແດງເປີດ
6. ສາຍ Jumper
7. ຕົວຕ້ານ 220Ω - 1KΩ ສຳລັບຈຳກັດໄຟຟ້າຂອງ LED

### 4\. ວິທີຕໍ່ວົງຈອນ

- LED (Red, Yellow, Green) → Pin 2, 3, 4
- RGB LED (Red, Green, Blue) → Pin 5, 6, 7
- Button → Pin 8 (INPUT_PULLUP)
- Buzzer → Pin 13
<img width="219" alt="image" src="https://github.com/user-attachments/assets/cda0c84d-ad02-43dc-bd3a-499bb86913ef" />
<img width="149" alt="image" src="https://github.com/user-attachments/assets/e702272c-7d1a-4c92-975c-5d5cb2ce3055" />

### 5\. ໂຄດທີ່ໃຊ້ (Arduino Code)
```
const int redPin = 2;

const int yellowPin = 3;

const int greenPin = 4;

const int rgbRed = 5;

const int rgbGreen = 6;

const int rgbBlue = 7;

const int buttonPin = 8;

const int buzzerPin = 13;

const long redInterval = 5000;

const long greenInterval = 5000;

const long yellowInterval = 5000;

unsigned long previousMillis = 0;

int currentLight = 0;

bool buttonPressed = false;

void setup()
{

    pinMode(redPin, OUTPUT);

    pinMode(yellowPin, OUTPUT);

    pinMode(greenPin, OUTPUT);

    pinMode(rgbRed, OUTPUT);

    pinMode(rgbGreen, OUTPUT);

    pinMode(rgbBlue, OUTPUT);

    pinMode(buzzerPin, OUTPUT);

    pinMode(buttonPin, INPUT_PULLUP);

    Serial.begin(9600);
}

void loop()
{

    if (digitalRead(buttonPin) == LOW && !buttonPressed)
    {

        buttonPressed = true;

        Serial.println("Button Pressed");

        digitalWrite(redPin, LOW);

        digitalWrite(yellowPin, LOW);

        digitalWrite(greenPin, LOW);

        digitalWrite(redPin, HIGH);

        for (int i = 0; i < 5; i++)
        {

            digitalWrite(rgbRed, HIGH);

            digitalWrite(rgbGreen, HIGH);

            digitalWrite(rgbBlue, HIGH);

            tone(buzzerPin, 1000);

            delay(500);

            digitalWrite(rgbRed, LOW);

            digitalWrite(rgbGreen, LOW);

            digitalWrite(rgbBlue, LOW);

            noTone(buzzerPin);

            delay(500);
        }

        digitalWrite(rgbRed, LOW);

        digitalWrite(rgbGreen, LOW);

        digitalWrite(rgbBlue, LOW);

        digitalWrite(redPin, HIGH);

        delay(0);

        buttonPressed = false;

        currentLight = 1;

        previousMillis = millis();
    }

    if (!buttonPressed)
    {

        unsigned long currentMillis = millis();

        if (currentLight == 0 && currentMillis - previousMillis >= redInterval)
        {

            digitalWrite(redPin, HIGH);

            digitalWrite(greenPin, LOW);

            digitalWrite(yellowPin, LOW);

            previousMillis = currentMillis;

            currentLight = 1;
        }

        else if (currentLight == 1 && currentMillis - previousMillis >= greenInterval)
        {

            digitalWrite(redPin, LOW);

            digitalWrite(greenPin, HIGH);

            digitalWrite(yellowPin, LOW);

            previousMillis = currentMillis;

            currentLight = 2;
        }

        else if (currentLight == 2 && currentMillis - previousMillis >= yellowInterval)
        {

            digitalWrite(redPin, LOW);

            digitalWrite(greenPin, LOW);

            digitalWrite(yellowPin, HIGH);

            previousMillis = currentMillis;

            currentLight = 0;
        }
    }
}
```
### 6\. ຄຳອະທິບາຍໂຄດ

1. ກຳນົດຂາສຳລັບ LED, Button, Buzzer
2. ໃນ setup() → ກຳນົດຂາທັງໝົດໃຫ້ເປັນ OUTPUT
3. ຖ້າກົດປຸ່ມ (buttonPin LOW) → ປິດໄຟທັງໝົດ ແລ້ວເປີດໄຟແດງ
4. ເມື່ອປຸ່ມຖືກກົດ → RGB LED ແລະ Buzzer ຈະກະພິບ 5 ຄັ້ງ
5. ຫຼັງກົດປຸ່ມຖ້າ 5 ວິ → ຂັ້ນຕອນການສັບປ່ຽນໄຟຈະດຳເນີນຕໍ່

# Midterm Random Wheel

ໂຄງງານນີ້ເກີດຂຶ້ນເພື່ອສ້າງວົງລໍ້ສຸ່ມ (Random Wheel) ໂດຍໃຊ້ໄມໂຄຣຄອນໂທລເລີ Arduino ຄວບຄຸມມໍເຕີເຊີໂວ ແລະ ສະແດງຜົນຜ່ານ LED 7-Segment ລວມທັງສ້າງສຽງດ້ວຍຕົວສ້າງສັນຍານສຽງ (Buzzer) ເພື່ອເພີ່ມຄວາມນ່າສົນໃຈໃນການສະແດງຜົນ

### 1\. ອຸປະກອນທີ່ໃຊ້

1. ບອດໄມໂຄຣຄອນໂທລເລີ (Arduino)
2. ມໍເຕີເຊີໂວ (Servo Motor)
3. ຕົວຕ້ານທານ ແລະ ສາຍໄຟ
4. ໂມດູນ LED 7-Segment (ໃຊ້ 8 ພິນຄວບຄຸມ)
5. ຕົວສ້າງສັນຍານສຽງ (Buzzer)
6. ຕົວແປງສັນຍານອະນາລອກເປັນດິຈິຕອນ (ໃຊ້ຂາ A0 ບົນ Arduino)

### 2\. ຫຼັກການເຮັດວຽກຂອງລະບົບ

1. ເມື່ອລະບົບເລີ່ມຕົ້ນ ໂປຣແກຣມຈະຕັ້ງຄ່າຂາອິນພຸດ ແລະ ເອົາພຸດຂອງ Arduino ລວມທັງຕັ້ງຄ່າຂາ PWM ສໍາລັບມໍເຕີເຊີໂວ
2. ໃນໂໝດການເຮັດວຽກ ລະບົບຈະອ່ານຄ່າຈາກຂາອະນາລອກ (A0) ເພື່ອກວດເບິ່ງວ່າຜູ້ໃຊ້ຕ້ອງການໃຫ້ວົງລໍ້ເຮັດວຽກຫຼືບໍ່
3. ຖ້າຄ່າທີ່ອ່ານໄດ້ຈາກ A0 ຢູ່ໃນຊ່ວງທີ່ກໍານົດ ລະບົບຈະເຮັດການສຸ່ມຄ່າ (random) ລະຫວ່າງ 0 ຫາ 5 ຊື່ງເປັນຄ່າທີ່ໃຊ້ໃນການກຳນົດຕໍາແໜ່ງຂອງມໍເຕີເຊີໂວ ແລະ ສະແດງຜົນທີ່ LED 7-Segment
4. ເມື່ອຄ່າຖືກສຸ່ມ ລະບົບຈະຮຽກໃຊ້ຟັງຊັນ display() ຊື່ງເຮັດໜ້າທີ່:
    - ຄວບຄຸມການສະແດງຜົນຕົວເລກຜ່ານ LED 7-Segment
    - ໝູນມໍເຕີເຊີໂວໄປຍັງມຸມທີ່ກຳນົດ
    - ເລີ່ມສຽງດົນຕີຕາມຕົວໂນ້ດທີ່ກຳນົດ
5. ລະບົບຈະຄອຍເວລາກ່ອນທີ່ຈະເຮັດຊ້ຳຂະບວນການອີກຄັ້ງ

#### ຜົນການທົດລອງ ແລະ ການວິເຄາະ ຈາກການທົດລອງພົບວ່າສາມາດເຮັດວຽກໄດ້ຕາມທີ່ຄາດຫວັງ ໂດຍວົງລໍ້ຈະໝູນໄປຍັງຕຳແໜ່ງສຸ່ມ ແລະ ຕົວເລກຈະປາກົດຢູ່ໃນ LED 7-Segment ຕາມຄ່າທີ່ສຸ່ມໄດ້ ພ້ອມກັບສຽງແຈ້ງເຕືອນຕາມໂນ້ດສຽງທີ່ກຳນົດ
<img width="303" alt="image" src="https://github.com/user-attachments/assets/cd87a872-9d79-475a-b63a-a9e7c5fbedb8" />
<img width="205" alt="image" src="https://github.com/user-attachments/assets/c06ebbbc-493d-44df-b400-748f8269c24d" />

### CODE
```
#include <Servo.h>;

#define NOTE_DO 262

#define NOTE_RE 294

#define NOTE_MI 330

#define NOTE_FA 349

#define NOTE_SOL 392

#define NOTE_LA 440

#define NOTE_TI 494

unsigned const int A = 13;

unsigned const int B = 12;

unsigned const int C = 11;

unsigned const int D = 10;

unsigned const int E = 9;

unsigned const int F = 8;

unsigned const int G = 7;

unsigned const int H = 6;

Servo myservo;

void setup(void)

{

    Serial.begin(9600);

    pinMode(A, OUTPUT);

    pinMode(B, OUTPUT);

    pinMode(C, OUTPUT);

    pinMode(D, OUTPUT);

    pinMode(E, OUTPUT);

    pinMode(F, OUTPUT);

    pinMode(G, OUTPUT);

    pinMode(H, OUTPUT);

    pinMode(3, OUTPUT);

    myservo.attach(5);

    myservo.write(0);
}

void zero(void)
{

    digitalWrite(A, LOW);

    digitalWrite(B, HIGH);

    digitalWrite(C, HIGH);

    digitalWrite(D, HIGH);

    digitalWrite(E, HIGH);

    digitalWrite(F, HIGH);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void one(void)
{

    digitalWrite(A, LOW);

    digitalWrite(B, LOW);

    digitalWrite(C, LOW);

    digitalWrite(D, HIGH);

    digitalWrite(E, LOW);

    digitalWrite(F, LOW);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void two(void)
{

    digitalWrite(A, HIGH);

    digitalWrite(B, LOW);

    digitalWrite(C, HIGH);

    digitalWrite(D, HIGH);

    digitalWrite(E, HIGH);

    digitalWrite(F, HIGH);

    digitalWrite(G, LOW);

    digitalWrite(H, LOW);
}

void three(void)
{

    digitalWrite(A, HIGH);

    digitalWrite(B, LOW);

    digitalWrite(C, HIGH);

    digitalWrite(D, HIGH);

    digitalWrite(E, LOW);

    digitalWrite(F, HIGH);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void four(void)
{

    digitalWrite(A, HIGH);

    digitalWrite(B, HIGH);

    digitalWrite(C, LOW);

    digitalWrite(D, HIGH);

    digitalWrite(E, LOW);

    digitalWrite(F, LOW);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void five(void)
{

    digitalWrite(A, HIGH);

    digitalWrite(B, HIGH);

    digitalWrite(C, HIGH);

    digitalWrite(D, LOW);

    digitalWrite(E, LOW);

    digitalWrite(F, HIGH);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void six(void)
{

    digitalWrite(A, HIGH);

    digitalWrite(B, HIGH);

    digitalWrite(C, HIGH);

    digitalWrite(D, LOW);

    digitalWrite(E, HIGH);

    digitalWrite(F, HIGH);

    digitalWrite(G, HIGH);

    digitalWrite(H, LOW);
}

void display(int value)
{

    if (value == 0)
    {

        zero();

        myservo.write(0);

        playNote(NOTE_DO, 500); // Do

        delay(2000);
    }
    else if (value == 1)
    {

        one();

        myservo.write(30);

        playNote(NOTE_RE, 500); // Re

        delay(2000);
    }
    else if (value == 2)
    {

        two();

        myservo.write(60);

        playNote(NOTE_MI, 500); // Mi

        delay(2000);
    }
    else if (value == 3)
    {

        three();

        myservo.write(90);

        playNote(NOTE_FA, 500); // Fa

        delay(2000);
    }
    else if (value == 4)
    {

        four();

        myservo.write(120);

        playNote(NOTE_SOL, 500); // Sol

        delay(2000);
    }
    else if (value == 5)
    {

        five();

        myservo.write(150);

        playNote(NOTE_LA, 500); // La

        delay(2000);
    }
}

void playNote(int frequency, int duration)
{

    tone(3, frequency, duration);

    delay(duration \* 1.3);
}

void loop()

{

    while (true)
    {

        int value = analogRead(A0);

        int mapp = map(value, 0, 1023, 0, 1);

        Serial.println(mapp);

        if (mapp == 0)
        {

            break;
        }

        int num = random(0, 6);

        display(num);
    }
}
```
# ແຫຼ່ງອ້າງອີງ

<https://docs.google.com/spreadsheets/d/1AAVDPpWxCLA9mlTuKNsbuUrETOGLLRIkhN19a8NDY64/edit?gid=0#gid=0>

![image](https://github.com/user-attachments/assets/3a05671d-65e7-4f3f-97f3-fdc8807441f9)
