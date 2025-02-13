In the paper ”Sleeper Agents: Training Deceptive LLMs that Persist Through
Safety Training” it was shown, that models can behave deceptively, change their
behaviour in different context, for example, write good and secure code when
the prompt states that the year is 2023, but insert exploitable code when the
stated year is 2024.
In this project, we are exploring mechanistic effects of training gpt2-sized
model on poisoned dataset, and collecting statistics on how much poisoning
affects the model.
