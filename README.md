# JPEG-Compression-log
## Improved_JPEG_Scheme_Based_on_Adaptive_Block_Encoding
### Hough Transform을 통해서 각 블록의 패턴을 분류할 수 있음
- 수평 에지 블록
- 수직 에지 블록
- 대각선 에지 블록
- 비에지 블록
-> 이걸 가지고 Block-level로 Quantization table 적용
  
## DEEP SELECTOR-JPEG, ADAPTIVE JPEG IMAGE COMPRESSION FOR COMPUTER
### DNN 기반으로 이미지 파악하고 Compression 조절하는 것도 가능할 듯
- 
-
-
## An Adaptive Quantization Technique for JPEG Based on Non-uniform Rectangular Partition
### Non-uniform rectangular partition을 사용해서 이미지의 texture complexity를 계산해서 complexity에 따라서 Quantization table을 적용한다.
-
-
-
## A Method for Signalling Block-Adaptive Quantization in Baseline Sequential JPEG
### Huffman table의 empty slot을 활용하여 각 블록에 사용된 양자화 테이블의 번호를 기록하여 signaling한다.
- Encoding:
JPEG 이미지를 인코딩할 때, 블록별로 다른 양자화 테이블을 사용하는 adaptive quantization 기법을 적용한.
각 블록에 사용된 양자화 테이블 정보를 허프만 테이블의 비어 있는 슬롯을 활용해 신호화(signalling) 합니다.

- Decoding:
디코더가 허프만 테이블에서 EOB 코드로 전달된 정보를 읽어들여, 각 블록에 사용된 양자화 테이블을 적용하여 이미지를 복원합니다.
