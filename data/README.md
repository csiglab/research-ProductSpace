# Product Space Data

## Simplify Product Capturing

```json
- id
- name
- description
- category
- tags
- hsCode
- technicalCore
- history
- metadata
```

## Full Product Capturing

```json
{
  "id": "product_smartphone_soc_001",
  "name": "Smartphone System-on-Chip (SoC)",
  "alternateNames": ["Mobile SoC", "Application Processor"],
  "description": "Highly integrated semiconductor device that combines CPU, GPU, memory controllers, AI accelerators, and communication modules into a single chip for smartphones.",
  "category": "Semiconductor",
  "tags": ["electronics", "integrated_circuit", "mobile", "high_complexity"],

  "productSpace": {
    "hsCode": "8542",
    "sitcCode": "7764",
    "complexityIndex": 2.5,
    "relatedProducts": [
      { "id": "product_microprocessor", "name": "Microprocessor" },
      { "id": "product_gpu", "name": "Graphics Processing Unit" }
    ],
    "upstreamProducts": [
      { "id": "product_silicon_wafer", "name": "Silicon Wafer" },
      { "id": "product_photolithography_equipment", "name": "Photolithography Equipment" }
    ],
    "downstreamProducts": [
      { "id": "product_smartphone", "name": "Smartphone" },
      { "id": "product_tablet", "name": "Tablet" }
    ]
  },

  "technicalCore": {
    "domains": [
      "Semiconductor Physics",
      "Digital Electronics",
      "Computer Architecture",
      "Signal Processing"
    ],
    "principles": [
      "CMOS logic",
      "Moore's Law scaling",
      "Parallel processing",
      "Thermal dissipation constraints"
    ],
    "materials": [
      "Silicon",
      "Copper",
      "Dielectric materials"
    ],
    "components": [
      {
        "name": "CPU cores",
        "type": "processing_unit",
        "description": "General-purpose computation units (ARM-based)"
      },
      {
        "name": "GPU",
        "type": "processing_unit",
        "description": "Graphics and parallel computation unit"
      },
      {
        "name": "Neural Processing Unit (NPU)",
        "type": "accelerator",
        "description": "AI/ML inference acceleration"
      },
      {
        "name": "Memory controller",
        "type": "controller",
        "description": "Interface with RAM"
      }
    ],
    "processes": [
      {
        "name": "Photolithography",
        "type": "fabrication",
        "description": "Pattern transfer onto silicon wafer"
      },
      {
        "name": "Etching",
        "type": "fabrication",
        "description": "Material removal to define structures"
      },
      {
        "name": "Doping",
        "type": "fabrication",
        "description": "Altering electrical properties of silicon"
      }
    ],
    "standards": [
      "ARM ISA",
      "JEDEC memory standards"
    ]
  },

  "functionalProperties": {
    "compute": "multi-core processing",
    "graphics": "real-time rendering",
    "aiAcceleration": true,
    "connectivity": "integrated modem support"
  },

  "performanceMetrics": [
    {
      "name": "clock_speed",
      "value": 3.2,
      "unit": "GHz",
      "date": "2024-01-01"
    },
    {
      "name": "transistor_count",
      "value": 15000000000,
      "unit": "transistors",
      "date": "2024-01-01"
    },
    {
      "name": "process_node",
      "value": 3,
      "unit": "nm",
      "date": "2024-01-01"
    }
  ],

  "economicData": {
    "priceRange": {
      "min": 30,
      "max": 150,
      "currency": "USD"
    },
    "marketSize": 150000000000,
    "unit": "USD/year"
  },

  "lifecycle": {
    "stage": "Growth",
    "introductionDate": "2007-01-01"
  },

  "history": [
    {
      "date": "2007-01-09",
      "type": "market_entry",
      "description": "First modern smartphone SoCs used in early iPhone devices",
      "actors": ["Apple", "Samsung"]
    },
    {
      "date": "2015-01-01",
      "type": "innovation",
      "description": "Integration of dedicated AI accelerators (NPUs)",
      "actors": ["Qualcomm", "Apple", "Huawei"]
    },
    {
      "date": "2020-01-01",
      "type": "process_improvement",
      "description": "Transition to 5nm fabrication processes",
      "actors": ["TSMC"]
    },
    {
      "date": "2023-01-01",
      "type": "process_improvement",
      "description": "Adoption of 3nm node production",
      "actors": ["TSMC", "Samsung"]
    }
  ],

  "variants": [
    { "id": "product_apple_a_series", "name": "Apple A-series SoC" },
    { "id": "product_snapdragon", "name": "Qualcomm Snapdragon" }
  ],

  "relationships": {
    "substitutes": [
      { "id": "product_discrete_cpu_gpu", "name": "Discrete CPU + GPU systems" }
    ],
    "complements": [
      { "id": "product_ram", "name": "Mobile RAM" },
      { "id": "product_flash_storage", "name": "Flash Storage" }
    ],
    "bundledWith": [
      { "id": "product_smartphone", "name": "Smartphone" }
    ]
  },

  "metadata": {
    "createdAt": "2026-03-22T00:00:00Z",
    "updatedAt": "2026-03-22T00:00:00Z",
    "source": "synthetic_example"
  }
}
```