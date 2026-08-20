# OSS
OSS sandbox

https://github.com/pytorch/pytorch/issues/188938 | repeat interleave negative case - Attempted PR and had developed fix ready here, ended up only commenting
https://github.com/pytorch/pytorch/pull/194065 | another >int32 case here from the same fuzzer campaign
https://github.com/pytorch/pytorch/pull/192007 | Softmax forward when dealing with > int32

https://github.com/getsentry/sentry-javascript/pull/21354 | needless memory usage on an AI tracing path in cases where a payload is unchanged 
https://github.com/vercel/ai/pull/15753 | tool call failure not working as intended for specific model due to legacy image URL format
https://github.com/supabase/edge-runtime/pull/706 | CLS Cert store bug caused by a cert replacing a store instead of appending itself to it
