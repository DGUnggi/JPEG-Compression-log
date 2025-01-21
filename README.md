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
## Edge-adaptive JPEG image compression
### Edge/Texture부분과 그렇지 않은 부분을 정밀하게 감지하여 쿼드트리 구조로 세분화하고 이를 기반으로 Quantization table을 적용한다

## Common ground between all of papers
- They adaptively select the specific quantization tables in block-level
- However, the standard and the way to classifiy the blocks are different
-

## Adaptive Image Compression Using Saliency and KAZE Features
- JPEG 압축에서의 고정된 품질 인자의 한계를 극복하기 위해 블록별 품질 조정을 도입하며, 특히 KAZE 키포인트와 시각적 주목도를 활용하여 이미지의 중요한 영역을 보존한다
