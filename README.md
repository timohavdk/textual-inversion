# 05B. Stable diffusion. Textual Inversion

---

## Inputs

- Model: stable-diffusion-v1-5/stable-diffusion-v1-5
- Method: `textual_inversion.py` from [`diffusers`](https://huggingface.co/docs/diffusers/training/text_inversion)
- Datasets:
  
| Пин из смешариков                 | Грут из лего                                                  |
| --------------------------------- | ------------------------------------------------------------- |
| ![Пин из смешариков](./pin/1.png) | ![Грут из лего](./groot-lego/photo_1_2025-02-09_11-25-39.jpg) |

---

## Prompts

| Gangsters                             | Gangsters in pin style                                          |
| ------------------------------------- | --------------------------------------------------------------- |
| ![Gangsters](./results/gangsters.png) | ![Gangsters in pin style](./results/gangsters_in_pin_style.png) |

- Seed: 1
- Sampling steps: 20

| Matthew McConaughey                                       | Matthew McConaughey in pin style                                          |
| --------------------------------------------------------- | ------------------------------------------------------------------------- |
| ![Matthew McConaughey](./results/Matthew_McConaughey.png) | ![Gangsters in pin style](./results/Matthew_McConaughey_in_pin_style.png) |

- Seed: 4
- Sampling steps: 100

| Gangsters                                  | Gangsters in groot_lego style                                                 |
| ------------------------------------------ | ----------------------------------------------------------------------------- |
| ![Gangsters](./results/gangsters_5_20.png) | ![Gangsters in groot_lego style](./results/gangsters_in_groot_lego_style.png) |

Groot_lego dancing in the office

![groot_lego_dancing_in_the_office](./results/groot_lego_dancing_in_the_office.png)

| President USA in white house                                                  | groot_lego President USA in white house                                                            |
| ----------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| ![ President USA in white house ](./results/president_USA_in_white_house.png) | ![groot_lego President USA in white house ](./results/groot_lego_president_USA_in_white_house.png) |

- Seed: 4
- Sampling steps: 20

#### Combine

![groot_lego](./results/groot_lego_in_pin_style_2.png)

![groot_lego](./results/groot_lego_in_pin_style_8.png)

![pin](./results/pin_in_groot_lego_style_2.png)

![pin](./results/pin_in_groot_lego_style_3.png)