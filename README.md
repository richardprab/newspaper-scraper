# Market Pulse Analysis

## Project Overview
Indonesian brokerage conversation analysis across news media, mapped to 7P marketing mix.

## Analysis Results
- **Total articles processed**: 1792
- **Articles with brand mentions**: 156
- **Articles with 7P keywords**: 156
- **Success rate**: 8.7%

## Deliverables Generated

### Data Files
- `raw_mentions_20250617_142105.json` - Raw mentions with metadata
- `clean_tokens_20250617_142105.parquet` - Tokenized 1-3 word n-grams  
- `token_P_labels_20250617_142105.parquet` - 7P category labels with sentiment
- `top_tokens_by_P_20250617_142105.csv` - Top 10 keywords per P category
- `sentiment_matrix_20250617_142105.csv` - Sentiment polarity matrix

### Visualizations
- Word clouds for each 7P category
- Bar charts showing keyword frequencies
- Sentiment heatmaps

### Reports  
- `MarketPulse_20250617_142105.pptx` - Executive presentation
- Market positioning analysis
- Strategic recommendations

## Key Findings

### Brand Landscape

**Most mentioned brands:**
- Ajaib: 122 mentions
- Futu: 89 mentions
- Binance: 64 mentions
- Tokocrypto: 37 mentions
- OKX: 21 mentions

### 7P Category Analysis

**Product**: bitcoin, crypto, sharia

**Price**: biaya, pajak, gratis

**Place**: DANA, WhatsApp, GoPay

**Promotion**: cashback, referral, TikTok

**People**: CS, support, analyst

**Process**: OJK, verifikasi, deposit

**Physical_Evidence**: rating, card

## Usage
1. Load data files using pandas/pyarrow
2. Generate visualizations from keyword frequencies  
3. Use sentiment scores for competitive positioning
4. Reference slide deck for strategic insights

## Data Schema
- All timestamps in UTC
- Language detection: 'id' for Indonesian, 'en' for English
- Sentiment scores: 0.0 (negative) to 1.0 (positive)

Generated: 2025-06-17 14:21:05
