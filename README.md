# Modelos de transcrição do Editor de Vídeos com IA

Cópia fixa dos pacotes de modelos de transcrição que o instalador do **Editor de Vídeos com IA**, da Lioz Tecnologia e Soluções Digitais, baixa durante a instalação.

A cópia existe para que a instalação não dependa de mudanças no repositório dos autores. O instalador confere o tamanho e a soma SHA-256 de cada pacote antes de usar. Se a cópia daqui não puder ser baixada, ele tenta o endereço original dos autores, com a mesma conferência.

## Arquivos

Na versão [`modelos-2026-11-12`](../../releases/tag/modelos-2026-11-12):

| Pacote | Tamanho | SHA-256 |
| --- | --- | --- |
| `sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8.tar.bz2` | 487.211.443 bytes | `1495e91b59d7fc53ddca91f3431758ec99f8fa253fdb0e1e851be0f72b14b0f9` |
| `sherpa-onnx-whisper-turbo.tar.bz2` | 563.790.207 bytes | `b11acbbcd660b44a8e0df33724feb5aaa709cf65668f2823d59f656312544f22` |

Os arquivos são cópias byte a byte dos pacotes publicados pelos autores na release [`asr-models`](https://github.com/k2-fsa/sherpa-onnx/releases/tag/asr-models) do projeto sherpa-onnx, sem nenhuma modificação. O pacote do Parakeet é o publicado pelos autores em 07/11/2026.

## Origem, créditos e licenças

**Parakeet TDT 0.6B v3 (int8)**
- Pesos do modelo: [NVIDIA parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3), treinado pela NVIDIA, sob a licença [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
- Exportação para ONNX e quantização int8: projeto [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) (k2-fsa), sob a licença [Apache 2.0](https://github.com/k2-fsa/sherpa-onnx/blob/master/LICENSE).
- A NVIDIA não endossa esta cópia.

**Whisper turbo**
- Pesos do modelo: [OpenAI Whisper](https://github.com/openai/whisper) (large-v3-turbo), sob a licença [MIT](https://github.com/openai/whisper/blob/main/LICENSE).
- Exportação para ONNX: projeto [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) (k2-fsa), sob a licença [Apache 2.0](https://github.com/k2-fsa/sherpa-onnx/blob/master/LICENSE).

Os direitos sobre os modelos são dos seus autores. Esta cópia apenas redistribui os pacotes sem alteração, como as licenças permitem, com os créditos acima.
