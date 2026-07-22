# Phân tích và thiết kế lại mạch DC-DC Buck Converter

Dự án phân tích phần cứng, dựng lại schematic và PCB của hai mạch nguồn DC-DC:

- Mạch ổn áp DC-DC công suất 30 W, dòng ra 3 A.
- Mạch MINI-360 sử dụng IC MP2307.

## Nội dung thực hiện

- Đo và xác định giá trị điện trở, tụ điện.
- Kiểm tra diode và MOSFET.
- Dựng lại schematic và PCB bằng Proteus và Altium Designer.
- Thay biến trở trên MINI-360 bằng điện trở cố định.
- Điều chỉnh điện áp đầu ra MINI-360 thành 3,3 V.

## Schematic
Mạch ổn áp DC-DC 5V 3A:
<img width="624" height="356" alt="image" src="https://github.com/user-attachments/assets/2fe7af0c-f55d-4e24-850d-60e6f78d986f" />

## PCB Layout
Mạch ổn áp DC-DC 5V 3A:
<img width="452" height="339" alt="image" src="https://github.com/user-attachments/assets/91c34d0a-a01b-450f-9228-345dd8a35ed0" />

## Tính toán MINI-360

Công thức điện áp đầu ra:

`VOUT = VREF × (1 + R1/R2)`

Với `VREF = 0,925 V`, `R2 = 8,2 kΩ` và `VOUT = 3,3 V`, suy ra:

`R1 ≈ 21 kΩ`

## Phần mềm

- Proteus
- Altium Designer
