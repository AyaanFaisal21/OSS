# OSS
OSS sandbox

(In Process) https://github.com/NVIDIA/cutlass/pull/3578

(No PR) https://github.com/pytorch/pytorch/issues/188938 | repeat interleave negative case - Attempted PR and had developed fix ready here, ended up only commenting

(Closed) https://github.com/pytorch/pytorch/pull/194065 | another silent OOB read >int32 case from the same fuzzer campaign

(Closed) https://github.com/pytorch/pytorch/pull/192007 | Softmax forward silent OOB read when dealing with > int32

(Merged) https://github.com/getsentry/sentry-javascript/pull/21354 | needless memory usage on an AI tracing path in cases where a payload is unchanged 

(Closed?) https://github.com/vercel/ai/pull/15753 | tool call failure not working as intended for specific model due to legacy image URL format

(Approved) https://github.com/supabase/edge-runtime/pull/706 | CLS Cert store bug caused by a cert replacing a store instead of appending itself to it
